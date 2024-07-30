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
    .schedule-table {
      box-shadow: none;
      border-radius: 0;
      overflow: visible;
    }
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
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
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

<table class="schedule-table">
  <thead>
    <tr>
      <th>Time</th>
      <th>Session</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="time-column">09:00 - 09:30</td>
      <td class="session-column">Welcome and Introduction</td>
      <td class="description-column">
        <ul>
          <li>Opening remarks</li>
          <li>Overview of workshop structure and objectives</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">09:30 - 11:00</td>
      <td class="session-column">Reflections on the Landscape</td>
      <td class="description-column">
        <ul>
          <li>Collaborative reflection on the existing landscape</li>
          <li>Talks, panels, and breakouts by modality (text, images, audio, video, and multimodal data)</li>
          <li>Topics:
            <ul>
              <li>Underlying frameworks</li>
              <li>Contextualization challenges</li>
              <li>Defining robust evaluations</li>
              <li>Incentive structures</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">11:00 - 11:15</td>
      <td class="session-column">Break</td>
      <td class="description-column"></td>
    </tr>
    <tr>
      <td class="time-column">11:15 - 12:45</td>
      <td class="session-column">Talks + Provocations</td>
      <td class="description-column">
        <ul>
          <li>Invited speakers on current technical evaluations for base models across all modalities</li>
          <li>Key social impact categories covered:
            <ul>
              <li>Bias and stereotyping</li>
              <li>Cultural values</li>
              <li>Performance disparities</li>
              <li>Privacy</li>
              <li>Financial and environmental costs</li>
              <li>Data moderator labor</li>
            </ul>
          </li>
          <li>Presentations of accepted provocations</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">12:45 - 13:45</td>
      <td class="session-column">Lunch Break</td>
      <td class="description-column"></td>
    </tr>
    <tr>
      <td class="time-column">13:45 - 15:45</td>
      <td class="session-column">Group Activity</td>
      <td class="description-column">
        <ul>
          <li>Participants break into groups focusing on key social impact categories</li>
          <li>Activities include:
            <ol>
              <li>Choosing Evaluations: Determining how to select evaluations from a large repository</li>
              <li>Reviewing Tools and Datasets: Assessing existing artifacts and identifying gaps</li>
              <li>Examining construct reliability, validity, and ranking methodologies</li>
            </ol>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">15:45 - 16:00</td>
      <td class="session-column">Break</td>
      <td class="description-column"></td>
    </tr>
    <tr>
      <td class="time-column">16:00 - 17:45</td>
      <td class="session-column">What's Next? Documentation + Resources</td>
      <td class="description-column">
        <ul>
          <li>Develop policy guidance highlighting impact categories, subcategories, and modalities requiring further investment</li>
          <li>Discussions on:
            <ol>
              <li>Documenting Methods: Creating a proposed framework for documenting evaluations</li>
              <li>Developing Shareable Resources: Improving evaluation repository and conceptualizing improved resources</li>
              <li>Underlying Frameworks: Examining foundational frameworks influencing evaluations</li>
              <li>Contextualization Challenges: Identifying challenges in contextualizing evaluations across different contexts</li>
              <li>Defining Robust Evaluations: Establishing criteria for robust and meaningful evaluations</li>
            </ol>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">17:45 - 18:00</td>
      <td class="session-column">Closing Remarks</td>
      <td class="description-column"></td>
    </tr>
  </tbody>
</table>

<script>
  document.addEventListener('DOMContentLoaded', (event) => {
    const table = document.querySelector('.schedule-table');
    const headers = table.querySelectorAll('th');
    const headerTexts = Array.from(headers).map(header => header.textContent);
    
    table.querySelectorAll('tbody tr').forEach(row => {
      row.querySelectorAll('td').forEach((cell, index) => {
        cell.setAttribute('data-label', headerTexts[index]);
        
        // Remove the data-label attribute for empty cells
        if (cell.textContent.trim() === '') {
          cell.removeAttribute('data-label');
        }
      });
    });
  });
</script>
