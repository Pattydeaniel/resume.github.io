<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Patrick Deaniel Alvarez | CV</title>

  <!-- ===== CSS START ===== -->
  <style>
    body {
      background: #f2f2f2;
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
    }

    .cv {
      max-width: 900px;
      background: #ffffff;
      margin: 30px auto;
      padding: 40px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }

    header {
      text-align: center;
      border-bottom: 2px solid #000;
      padding-bottom: 15px;
    }

    header h1 {
      font-size: 28px;
      margin-bottom: 5px;
    }

    header h2 {
      font-size: 16px;
      letter-spacing: 2px;
      margin-bottom: 10px;
      font-weight: normal;
    }

    .contact {
      font-size: 14px;
    }

    section {
      margin-top: 25px;
    }

    h3 {
      border-bottom: 1px solid #000;
      padding-bottom: 5px;
      margin-bottom: 10px;
      font-size: 18px;
    }

    .job {
      margin-bottom: 15px;
    }

    .job-header {
      display: flex;
      justify-content: space-between;
      font-weight: bold;
      font-size: 14px;
    }

    ul {
      margin-left: 20px;
    }

    li {
      margin-bottom: 6px;
    }

    .education li,
    .skills li {
      display: flex;
      justify-content: space-between;
    }

    button {
      margin-top: 30px;
      padding: 10px 25px;
      background: #000;
      color: #fff;
      border: none;
      cursor: pointer;
      font-size: 14px;
    }

    button:hover {
      opacity: 0.8;
    }

    @media (max-width: 600px) {
      .job-header {
        flex-direction: column;
      }

      .education li {
        flex-direction: column;
      }
    }

    @media print {
      button {
        display: none;
      }
    }
  </style>
  <!-- ===== CSS END ===== -->

</head>
<body>

<div class="cv">
  <header>
    <h1>Patrick Deaniel Alvarez</h1>
    <h2>INFORMATION TECHNOLOGY SPECIALIST</h2>
    <p class="contact">
      San Mateo, Rizal | 09774501885 | alvarez.patrick2017@gmail.com
    </p>
  </header>

  <section>
    <h3>Objective</h3>
    <p>
      As a fresh graduate in Information Technology, my goal is to begin my
      professional journey in your company IT department where I can apply my
      academic knowledge, develop new skills, and gain valuable hands-on
      experience. I am eager to learn from experienced professionals, take on new
      challenges, and grow both personally and professionally. With a strong
      motivation to contribute to the success of the team, I aim to become an
      effective part of your organization by supporting IT operations, adapting
      to emerging technologies, and continuously improving my technical and
      problem-solving abilities.
    </p>
  </section>

  <section>
    <h3>Experience</h3>

    <div class="job">
      <div class="job-header">
        <span>PRE-INTERNSHIP | TECH SUPPORT</span>
        <span>January 2025 – April 2025</span>
      </div>
      <ul>
        <li>Designed layouts and visuals using Adobe Photoshop for IT-related projects and documentation.</li>
        <li>Assembled and disassembled personal computers for maintenance, upgrades, and troubleshooting.</li>
        <li>Diagnosed and repaired hardware and software issues to restore system functionality.</li>
        <li>Conducted routine maintenance of computers, peripherals, and other IT equipment.</li>
      </ul>
    </div>

    <div class="job">
      <div class="job-header">
        <span>ACQUIRE BPO | BACK OFFICE</span>
        <span>February 2024 – October 2024</span>
      </div>
      <ul>
        <li>Processed vehicle images from toll gates by accurately typing plate numbers.</li>
        <li>Reviewed weekly performance reports to identify and correct errors.</li>
        <li>Ensured compliance with company standards through precise data processing.</li>
        <li>Adapted to workflow changes and supported team productivity goals.</li>
      </ul>
    </div>
  </section>

  <section>
    <h3>Education</h3>
    <ul class="education">
      <li><span><strong>Colegio de Montalban</strong> – BS Information Technology</span><span>2025</span></li>
      <li><span><strong>Eastern Star Academy</strong> – ICT Strand</span><span>2021</span></li>
      <li><span><strong>Guinayang National High School</strong></span><span>2019</span></li>
      <li><span><strong>Maly Elementary School</strong></span><span>2015</span></li>
    </ul>
  </section>

  <section>
    <h3>Skills & Ability</h3>
    <ul class="skills">
      <li>Programmer (HTML, CSS, JS, PHP, VB.NET, C#, C)</li>
      <li>Networking and Configuration</li>
      <li>Team collaboration and adaptability</li>
      <li>Problem-solving and troubleshooting mindset</li>
      <li>Ability to meet deadlines with high-quality output</li>
    </ul>
  </section>

  <button onclick="printCV()">Download / Print CV</button>
</div>

<!-- ===== JAVASCRIPT START ===== -->
<script>
  function printCV() {
    window.print();
  }
</script>
<!-- ===== JAVASCRIPT END ===== -->

</body>
</html>
