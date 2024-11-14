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

# Workshop Schedule (Tentative)

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
          <li>Opening Remarks</li>
          <li>Overview of Workshop Structure and Objectives</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">09:30 - 10:30</td>
      <td class="session-column">Opening Panel: Reflections on the Landscape</td>
      <td class="description-column">
        <ul>
          <li>Panel Discussion on AI Evaluation Challenges</li>
          <li>Panelists: Abeba Birhane, Su Lin Blodgett, Abigail Jacobs, Lee Wan Sie</li>
          <li>Topics:
            <ul>
              <li>Underlying frameworks and incentive structures</li>
              <li>Defining robust evaluations and contextual challenges</li>
              <li>Multimodal evaluation needs (text, images, audio, video)</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">10:30 - 11:15</td>
      <td class="session-column">Oral Session 1: Provocations and Ethics in AI Evaluation</td>
      <td class="description-column">
        <ul>
          <li>"Provocation: Who benefits from 'inclusion' in Generative AI?"</li>
          <li>"(Mis)use of nude images in machine learning research"</li>
          <li>"Evaluating Refusal"</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">11:15 - 11:30</td>
      <td class="session-column">Break</td>
      <td class="description-column"></td>
    </tr>
    <tr>
      <td class="time-column">11:30 - 12:15</td>
      <td class="session-column">Oral Session 2: Multimodal and Cross-Cultural Evaluation Methods</td>
      <td class="description-column">
        <ul>
          <li>"JMMMU: A Japanese Massive Multi-discipline Multimodal Understanding Benchmark"</li>
          <li>"Critical human-AI use scenarios and interaction modes for societal impact evaluations"</li>
          <li>"Cascaded to End-to-End: New Safety, Security, and Evaluation Questions for Audio Language Models"</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">12:15 - 14:15</td>
      <td class="session-column">Lunch and Poster Session</td>
      <td class="description-column">
        <ul>
          <li>12:15 - 12:45 PM: Lunch setup and networking</li>
          <li>12:45 - 14:15 PM: Poster presentations</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">14:15 - 15:00</td>
      <td class="session-column">Oral Session 3: Systematic Approaches to AI Impact Assessment</td>
      <td class="description-column">
        <ul>
          <li>"GenAI Evaluation Maturity Framework (GEMF)"</li>
          <li>"AIR-Bench 2024: Safety Evaluation Based on Risk Categories"</li>
          <li>"Evaluating Generative AI Systems is a Social Science Measurement Challenge"</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">15:00 - 15:45</td>
      <td class="session-column">Group Activity: Building Evaluation Frameworks</td>
      <td class="description-column">
        <ul>
          <li>Breakout Groups on Key Social Impact Categories</li>
          <li>Activities include:
            <ul>
              <li>Choosing Evaluations: Selecting relevant evaluations from a large repository</li>
              <li>Reviewing Tools and Datasets: Assessment of current tools and gaps</li>
              <li>Evaluating Reliability and Validity: Exploring construct validity and ranking methods</li>
            </ul>
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
      <td class="session-column">What's Next? Coalition Development</td>
      <td class="description-column">
        <ul>
          <li>Overview of Ongoing Social Impact Projects</li>
          <li>Interactive Discussion: Launching the Coalition on Social Impact Evaluation</li>
          <li>Topics include:
            <ul>
              <li>Developing criteria for evaluating evaluations</li>
              <li>Creating proposed documentation standards</li>
              <li>Building out resource repositories</li>
              <li>Conducting reviews and publishing annual scorecards</li>
              <li>Establishing next steps for collaboration and coalition goals</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">17:45 - 18:00</td>
      <td class="session-column">Closing Remarks</td>
      <td class="description-column">
        <ul>
          <li>Summary of key insights and next steps</li>
        </ul>
      </td>
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
