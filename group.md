
---
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 25%;
  margin-bottom: 16px;
  padding: 0 8px;
  overflow: visible;
  overflow-wrap: normal;
}

@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
    overflow: visible;
    overflow-wrap: normal;
  }
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

.container {
  padding: 0 16px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}
---
</style>
</head>
<body>

<h2>principal investigator</h2>

<div class="row">
  <div class="column">
    <div class="card">
      <img src="/img/Ioan.jpg" alt="Jim" style="width:100%">
      <div class="container" style="width:100%">
        <h2>Ioan Andricioaei</h2>
        <p>andricio@uci.edu</p>
      </div>
    </div>
  </div>
</div>

<h2>Graduate Students</h2>

<div class="row">
  <div class="column">
    <div class="card">
      <img src="/img/Anupam.jpg" alt="Anupam" style="width:100%">
      <div class="container" style="width:100%">
        <h2>Anupam Chatterjee</h2>
        <p>Research Interest: Enhanced sampling method development, Simulation of nucleic acids</p>
        <p>anupamc@uci.edu</p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="/img/Jim.jpg" alt="Jim" style="width:100%">
      <div class="container" style="width:100%">
        <h2>James McSally</h2>
        <p>Research Interests: Nucleotide conformational changes of RNA and DNA and the reweighting of Langevin trajectories. </p>
        <p>jmcsally@uci.edu</p>
      </div>
    </div>
  </div>
  <div class="column">
    <div class="card">
      <img src="/img/Moises.isesjpg" alt="Moises" style="width:100%">
      <div class="container" style="width:100%">
        <h2>Moises Romero</h2>
        <p>Research Interest: Enhanced sampling method development, Simulation of nucleic acids</p>
        <p>dray1@uci.edu</p>
      </div>
    </div>
  </div>
  <div class="column">
    <div class="card">
      <img src="/img/Dhiman.jpg" alt="Dhiman" style="width:100%">
      <div class="container" style="width:100%">
        <h2>Dhiman Ray</h2>
        <p>Research Interest: Enhanced sampling method development, Simulation of nucleic acids</p>
        <p>dray1@uci.edu</p>
      </div>
    </div>
  </div>
</div>

</body>
</html>
