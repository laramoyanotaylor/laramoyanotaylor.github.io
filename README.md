<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Lara Moyano Taylor</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      background-color: #164b35;
      color: white;
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.6;
    }

    .page {
      width: min(900px, 90%);
      margin: 0 auto;
      padding: 70px 0;
    }

    .introduction {
      display: grid;
      grid-template-columns: 1fr 280px;
      align-items: center;
      gap: 60px;
      min-height: 60vh;
    }

    h1 {
      margin: 0 0 20px;
      font-size: clamp(2.6rem, 7vw, 5rem);
      line-height: 1.05;
    }

    h2 {
      margin-top: 0;
      font-size: 1.8rem;
    }

    a {
      color: white;
      text-decoration-thickness: 1px;
      text-underline-offset: 4px;
    }

    a:hover {
      opacity: 0.75;
    }

    .contact {
      margin: 6px 0;
    }

    .portrait {
      width: 100%;
      aspect-ratio: 1 / 1;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid white;
    }

    section {
      padding: 45px 0;
      border-top: 1px solid rgba(255, 255, 255, 0.35);
    }

    .education-item {
      margin-bottom: 25px;
    }

    .education-item h3 {
      margin-bottom: 4px;
    }

    .education-item p {
      margin: 0;
    }

    @media (max-width: 700px) {
      .page {
        padding-top: 40px;
      }

      .introduction {
        grid-template-columns: 1fr;
        min-height: auto;
        gap: 35px;
        padding-bottom: 50px;
      }

      .portrait {
        width: min(260px, 80%);
        grid-row: 1;
      }
    }
  </style>
</head>

<body>
  <main class="page">

    <header class="introduction">
      <div>
        <h1>Lara Moyano Taylor</h1>

        <p class="contact">
          <a href="mailto:3253134M@student.gla.ac.uk">
            3253134M@student.gla.ac.uk
          </a>
        </p>

        <p class="contact">
          <a href="mailto:larasmt04@gmail.com">
            larasmt04@gmail.com
          </a>
        </p>

        <p class="contact">
          <a href="https://github.com/laramoyanotaylor">
            GitHub
          </a>
        </p>

        <p class="contact">
          <a href="https://www.linkedin.com/in/lara-moyano-taylor/">
            LinkedIn
          </a>
        </p>
      </div>

      <img
        class="portrait"
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
        <h3>PhD in Quantum hardware and device simulations</h3>
        <p>University of Glasgow, AQT CDT, 2026–present</p>
        <p>Research topic: Simulating material effects in qubits and investigating their impact on fault-tolerant quantum computing.</p>
        <p>Supervisor: Prof. Vihar Georgiev</p>
      </div>

      <div class="education-item">
        <h3>MSc Theoretical Physics</h3>
        <p>University of Edinburgh, 2025-2026</p>
        <p>Dissertation: Quantum error correction with GKP codes.</p>
        <p>Supervisor: Dr Joschka Roffe & Dr Steven Thomson</p>
      </div>

      <div class="education-item">
        <h3>BSc Physics</h3>
        <p>University of Bristol, 2022–2025</p>
        <p>1st Class with Honours</p>
        <p>Dissertation: N-body simulations in VR</p>
        <p>Supervisor: Dr Simon Hannah</p>
      </div>
    </section>

  </main>
</body>
</html>
