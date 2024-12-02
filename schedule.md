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

# Workshop Schedule 📅

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
      <td class="time-column">9:00 - 9:15 AM</td>
      <td class="session-column">☕ Coffee</td>
      <td class="description-column">⏰😴📢⬆</td>
    </tr>
    <tr>
      <td class="time-column">9:15 - 9:30 AM</td>
      <td class="session-column">👋 Welcome and Introduction</td>
      <td class="description-column">
        <ul>
          <li>Opening Remarks</li>
          <li>Overview of Workshop Structure and Objectives</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">9:30 - 10:30 AM</td>
      <td class="session-column">🎤 Opening Panel: Reflections on the Landscape</td>
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
          <li>Q&A</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">10:30 - 11:30 AM</td>
      <td class="session-column">💭 Oral Session 1: Provocations and Ethics in AI Evaluation</td>
      <td class="description-column">
        <ul>
          <li>Presentations (25 min):
            <ul>
              <li>"Provocation: Who benefits from 'inclusion' in Generative AI?"</li>
              <li>"(Mis)use of nude images in machine learning research"</li>
              <li>"Evaluating Refusal"</li>
            </ul>
          </li>
          <li>Breakout (35 min):
            <ul>
              <li>Group Discussion (20 min): Ethics and Bias in Evaluation Design, Refusal and Boundary Setting, Research Ethics and Data Usage</li>
              <li>Report Back (15 min)</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">11:30 AM - 12:30 PM</td>
      <td class="session-column">🌏 Oral Session 2: Multimodal and Cross-Cultural Evaluation Methods</td>
      <td class="description-column">
        <ul>
          <li>Presentations (25 min):
            <ul>
              <li>"JMMMU: A Japanese Massive Multi-discipline Multimodal Understanding Benchmark"</li>
              <li>"Critical human-AI use scenarios and interaction modes for societal impact evaluations"</li>
              <li>"Cascaded to End-to-End: New Safety, Security, and Evaluation Questions for Audio Language Models"</li>
            </ul>
          </li>
          <li>Breakout (35 min):
            <ul>
              <li>Group Discussion (20 min): Language, Image, Audio, Video, Cross-Culture</li>
              <li>Report Back (15 min)</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">12:30 - 2:30 PM</td>
      <td class="session-column">🍽️ Lunch and Poster Session</td>
      <td class="description-column">
        <ul>
          <li>12:30 - 1:15 PM: Lunch and Networking</li>
          <li>1:15 - 2:30 PM: Poster Presentations</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">2:30 - 3:00 PM</td>
      <td class="session-column">📊 Oral Session 3: Systematic Approaches to AI Impact Assessment</td>
      <td class="description-column">
        <ul>
          <li>Presentations:
            <ul>
              <li>"GenAI Evaluation Maturity Framework (GEMF)"</li>
              <li>"AIR-Bench 2024: Safety Evaluation Based on Risk Categories"</li>
              <li>"Evaluating Generative AI Systems is a Social Science Measurement Challenge"</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">3:00 - 3:30 PM</td>
      <td class="session-column">🔄 Break</td>
      <td class="description-column"></td>
    </tr>
    <tr>
      <td class="time-column">3:30 - 4:05 PM</td>
      <td class="session-column">💡 Oral Session 3 Breakout</td>
      <td class="description-column">
        <ul>
          <li>Group Discussion (20 min):
            <ul>
              <li>Choosing Evaluations: Selecting relevant evaluations from a large repository</li>
              <li>Reviewing Tools and Datasets: Assessment of current tools and gaps</li>
              <li>Evaluating Reliability and Validity: Exploring construct validity and ranking methods</li>
            </ul>
          </li>
          <li>Report Back (15 min)</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">4:05 - 5:00 PM</td>
      <td class="session-column">🤝 What's Next? Coalition Development</td>
      <td class="description-column">
        <ul>
          <li>Recap and Teasers (15 min):
            <ul>
              <li>Overview of coalition groups</li>
            </ul>
          </li>
          <li>Interactive Discussion (40 min):
            <ul>
              <li>Measurement Modeling</li>
              <li>Developing Criteria for Evaluating Evaluations</li>
              <li>Documentation: Creating Proposed Documentation Standards</li>
              <li>Eval Repository: Building Out Resource Repositories</li>
              <li>Scorecard/Checklist: Conducting Reviews and Publishing Annual Scorecards</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="time-column">5:00 - 5:30 PM</td>
      <td class="session-column">👋 Closing Session</td>
      <td class="description-column">
        <ul>
          <li>Summary of Key Insights and Next Steps</li>
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
