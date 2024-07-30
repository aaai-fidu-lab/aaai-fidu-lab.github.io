---
title: Schedule
nav: true
---

<style>
  .schedule-table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0;
    margin-bottom: 20px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    overflow: hidden;
  }
  .schedule-table th, .schedule-table td {
    border-right: 1px solid #e0e0e0;
    border-bottom: 1px solid #e0e0e0;
    padding: 12px;
    text-align: left;
  }
  .schedule-table th:last-child, .schedule-table td:last-child {
    border-right: none;
  }
  .schedule-table tr:last-child td {
    border-bottom: none;
  }
  .schedule-table th {
    background-color: #f0f0f0;
    font-weight: bold;
  }
  .schedule-table tr:nth-child(even) {
    background-color: #f8f9fa;
  }
  .schedule-table tr:hover {
    background-color: #e9ecef;
  }
  .time-column {
    white-space: nowrap;
    font-weight: bold;
  }
  .session-column {
    font-weight: bold;
  }
  .description-column ul {
    margin: 0;
    padding-left: 20px;
  }
  @media (max-width: 768px) {
    .schedule-table, .schedule-table tbody, .schedule-table tr, .schedule-table td {
      display: block;
    }
    .schedule-table thead {
      display: none;
    }
    .schedule-table tr {
      margin-bottom: 15px;
      border: 1px solid #e0e0e0;
      border-radius: 8px;
      overflow: hidden;
    }
    .schedule-table td {
      border: none;
      position: relative;
      padding-left: 50%;
    }
    .schedule-table td:before {
      content: attr(data-label);
      position: absolute;
      left: 6px;
      width: 45%;
      padding-right: 10px;
      white-space: nowrap;
      font-weight: bold;
    }
    .time-column, .session-column {
      background-color: #f0f0f0;
    }
    .schedule-table td:empty {
      display: none;
    }
  }
</style>

# Workshop Structure (Tentative)

Total Duration: 8 Hours

| Time | Session | Description |
|:-----|:--------|:------------|
| 09:00 - 09:30 | Welcome and Introduction | <ul><li>Opening remarks</li><li>Overview of workshop structure and objectives</li></ul> |
| 09:30 - 11:00 | Reflections on the Landscape | <ul><li>Collaborative reflection on the existing landscape</li><li>Talks, panels, and breakouts by modality (text, images, audio, video, and multimodal data)</li><li>Topics:<ul><li>Underlying frameworks</li><li>Contextualization challenges</li><li>Defining robust evaluations</li><li>Incentive structures</li></ul></li></ul> |
| 11:00 - 11:15 | Break | |
| 11:15 - 12:45 | Talks + Provocations | <ul><li>Invited speakers on current technical evaluations for base models across all modalities</li><li>Key social impact categories covered:<ul><li>Bias and stereotyping</li><li>Cultural values</li><li>Performance disparities</li><li>Privacy</li><li>Financial and environmental costs</li><li>Data moderator labor</li></ul></li><li>Presentations of accepted provocations</li></ul> |
| 12:45 - 13:45 | Lunch Break | |
| 13:45 - 15:45 | Group Activity | <ul><li>Participants break into groups focusing on key social impact categories</li><li>Activities include:<ol><li>Choosing Evaluations: Determining how to select evaluations from a large repository</li><li>Reviewing Tools and Datasets: Assessing existing artifacts and identifying gaps</li><li>Examining construct reliability, validity, and ranking methodologies</li></ol></li></ul> |
| 15:45 - 16:00 | Break | |
| 16:00 - 17:45 | What's Next? Documentation + Resources | <ul><li>Develop policy guidance highlighting impact categories, subcategories, and modalities requiring further investment</li><li>Discussions on:<ol><li>Documenting Methods: Creating a proposed framework for documenting evaluations</li><li>Developing Shareable Resources: Improving evaluation repository and conceptualizing improved resources</li><li>Underlying Frameworks: Examining foundational frameworks influencing evaluations</li><li>Contextualization Challenges: Identifying challenges in contextualizing evaluations across different contexts</li><li>Defining Robust Evaluations: Establishing criteria for robust and meaningful evaluations</li></ol></li></ul> |
| 17:45 - 18:00 | Closing Remarks | |

<script>
  document.addEventListener('DOMContentLoaded', (event) => {
    const table = document.querySelector('table');
    table.classList.add('schedule-table');
    const headers = table.querySelectorAll('th');
    const headerTexts = Array.from(headers).map(header => header.textContent);
    
    table.querySelectorAll('tr').forEach(row => {
      row.querySelectorAll('td').forEach((cell, index) => {
        cell.setAttribute('data-label', headerTexts[index]);
        if (index === 0) cell.classList.add('time-column');
        if (index === 1) cell.classList.add('session-column');
        if (index === 2) cell.classList.add('description-column');
        
        // Remove the data-label attribute for empty cells
        if (cell.textContent.trim() === '') {
          cell.removeAttribute('data-label');
        }
      });
    });
  });
</script>
