
<table>
  <tr>
    <td width="34.25%">
      <img src="https://images.unsplash.com/vector-1793617029992-080e067eb92d?q=80&w=774&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=NHwxMjA3fDA%3D" width="100%">
    </td>
    <td width="65.75%">
      <img src="https://plus.unsplash.com/premium_photo-1795003141687-65b73b177d1d?q=80&w=1548&auto=format&fit=crop&ixlib=rb-4.1.0" width="100%">
    </td>
  </tr>
</table>



<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
  :root {
    color-scheme: dark;
  }

  body {
    margin: 0;
    padding: 40px;
    background: #0d1117;
    color: #e6edf3;
    font-family: -apple-system, BlinkMacSystemFont,
                 "Segoe UI", Helvetica, Arial, sans-serif;
  }

  .skills {
    display: grid;
    grid-template-columns: repeat(4, minmax(0, 1fr));
    gap: 32px;
    max-width: 1200px;
    margin: auto;
  }

  .column-title {
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 1.2px;
    color: #8b949e;
    padding-top: 15px;
    padding-bottom: 16px;
    margin-bottom: 28px;
    border-bottom: 1px solid #30363d;
  }

  .category {
    margin-bottom: 22px;
  }

  .category h3 {
    font-size: 13px;
    font-weight: 600;
    margin: 0 0 6px;
    color: #e6edf3;
  }

  .category p {
    font-size: 12px;
    line-height: 1.7;
    color: #8b949e;
    margin: 0;
  }

  @media (max-width: 800px) {
    .skills {
      grid-template-columns: repeat(2, 1fr);
    }
  }

  @media (max-width: 480px) {
    .skills {
      grid-template-columns: 1fr;
    }
  }
</style>
</head>

<body>

<div class="skills">

  <!-- SOFTWARE -->
  <section>
    <div class="column-title">01 / SOFTWARE</div>

    <div class="category">
      <h3>Programming</h3>
      <p>Python · C# · MATLAB · GDScript · NI LabVIEW</p>
    </div>

    <div class="category">
      <h3>Python Ecosystem</h3>
      <p>PyTorch · TensorFlow · Keras · NumPy · Pandas · SciPy · scikit-learn · OpenCV</p>
    </div>

    <div class="category">
      <h3>Development & Integration</h3>
      <p>Git · Docker · CI/CD</p>
    </div>
  </section>

  <!-- ARTIFICIAL INTELLIGENCE -->
  <section>
    <div class="column-title">02 / ARTIFICIAL INTELLIGENCE</div>

    <div class="category">
      <h3>Machine Learning</h3>
      <p>Supervised & Unsupervised Learning</p>
    </div>

    <div class="category">
      <h3>Deep Learning</h3>
      <p>CNNs · RNNs · LSTMs · Transformers</p>
    </div>

    <div class="category">
      <h3>Generative AI</h3>
      <p>LLMs · Autoencoders · VAEs · GANs · WGANs</p>
    </div>

    <div class="category">
      <h3>Computer Vision</h3>
    </div>
  </section>

  <!-- ROBOTICS -->
  <section>
    <div class="column-title">03 / ROBOTICS & AUTONOMY</div>

    <div class="category">
      <h3>Robotics</h3>
      <p>Robot Kinematics & Dynamics · Trajectory Planning · Visual Servo Control · Motion Planning</p>
    </div>

    <div class="category">
      <h3>Autonomous Vehicles</h3>
      <p>Perception · Sensor Fusion · Localization · Decision Making & Planning · Control</p>
    </div>
  </section>

  <!-- ENGINEERING -->
  <section>
    <div class="column-title">04 / ENGINEERING & SIMULATION</div>

    <div class="category">
      <h3>Electrical Engineering</h3>
      <p>Electronics · Power Electronics · PCB Design (Autodesk Fusion) · Control Engineering</p>
    </div>

    <div class="category">
      <h3>Modeling & Simulation</h3>
      <p>Simulink · Simscape · COMSOL Multiphysics · Godot · Blender</p>
    </div>
  </section>

</div>

</body>
</html>

