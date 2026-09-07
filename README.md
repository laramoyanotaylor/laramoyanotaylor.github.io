<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lara Moyano Taylor</title>

  <style>
    body {
      margin: 0;
      background: #164b35;
      color: white;
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }

    main {
      max-width: 850px;
      margin: auto;
      padding: 60px 25px;
    }

    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 50px;
      margin-bottom: 60px;
    }

    img {
      width: 250px;
      height: 250px;
      object-fit: cover;
    }

    section {
      margin-top: 45px;
    }

    a {
      color: white;
    }

    .education-item {
      margin-bottom: 30px;
    }

    .education-item h3 {
      margin-bottom: 5px;
    }

    .education-item p {
      margin: 3px 0;
    }

    @media (max-width: 650px) {
      header {
        flex-direction: column-reverse;
        align-items: flex-start;
      }
    }
  </style>
</head>

<body>
  <main>
    <header>
      <div>
        <h1>Lara Moyano Taylor</h1>

        <p>
          <a href="mailto:3253134M@student.gla.ac.uk">
            3253134M@student.gla.ac.uk
          </a>
        </p>

        <p>
          <a href="mailto:larasmt04@gmail.com">
            larasmt04@gmail.com
          </a>
        </p>

        <p>
          <a href="https://github.com/laramoyanotaylor">
            GitHub
          </a>
        </p>

        <p>
          <a href="https://www.linkedin.com/in/lara-moyano-taylor/">
            LinkedIn
          </a>
        </p>
      </div>

      <img
        src="1000095109_1.jpg"
        alt="Portrait of Lara Moyano Taylor"
      >
    </header>

    <section>
      <h2>Academic Interests</h2>

      <ul>
        <li>Quantum hardware simulations</li>
        <li>Quantum information and quantum computing</li>
        <li>Quantum error correction</li>
      </ul>
    </section>

    <section>
      <h2>Education</h2>

      <div class="education-item">
        <h3>PhD in Quantum Hardware and Device Simulations</h3>
        <p>University of Glasgow, AQT CDT, 2026–present</p>
        <p>
          Research topic: Simulating material effects in qubits and
          investigating their impact on fault-tolerant quantum computing.
        </p>
        <p>Supervisor: Professor Vihar Georgiev</p>
      </div>

      <div class="education-item">
        <h3>MSc Theoretical Physics</h3>
        <p>University of Edinburgh, 2025–2026</p>
        <p>Dissertation: Quantum error correction with GKP codes</p>
        <p>Supervisors: Dr Joschka Roffe and Dr Steven Thomson</p>
      </div>

      <div class="education-item">
        <h3>BSc Physics</h3>
        <p>University of Bristol, 2022–2025</p>
        <p>First-class honours</p>
        <p>Dissertation: N-body simulations in VR</p>
        <p>Supervisor: Dr Simon Hannah</p>
      </div>
    </section>
  </main>
</body>
</html>
