# Solutions

Do your best to work through each challenge. If you've been stuck on any particular challenge for more than 20 minutes take a peek at the solution. There is of course more than one way to solve each of these problems, so feel free to use thes solutions as inspiration or food for thought.

<details>
  <summary>Challenge #1</summary>

  ```js
  renderPlanets() {
    return planetData.map((planet) => {
      return <p>{planet.name}</p>;
    });
  };
  ```
</details>

<br>

<details>
  <summary>Challenge #2</summary>

  ```js
  renderPlanets() {
    return planetData.map((planet) => {
      return (
        <div>
          <h4>{planet.name}</h4>
          <p>Diameter: {planet.diameter}</p>
        </div>
      )
    });
  }
  ```
</details>

<br>

<details>
  <summary>Challenge #3</summary>

  ```js
  renderPlanets() {
    return planetData.map((planet) => {
      return (
        <div>
          <h4>{planet.name}</h4>
          <p>Length of Day: {planet.lengthOfDay}</p>
        </div>
      );
    })
  }
  ```
</details>

<br>

<details>
  <summary>Challenge #4</summary>

  ```js
  renderPlanets() {
    const Earth = planetData.find((planet) => {
      return planet.name === 'Earth';
    });

    return (
      <div>
        <h4>{Earth.name}</h4>
        <p>Diameter: {Earth.diameter}</p>
        <p>Length of Day: {Earth.lengthOfDay} hours</p>
      </div>
    )
  };
  ```
</details>

<br>

<details>
  <summary>Challenge #5</summary>

  ```js
  renderPlanets() {
    const foundPlanet = planetData.find((planet) => {
      return planet.lengthOfDay === 10.7;
    });

    return (
      <div>
        <h4>{foundPlanet.name}</h4>
        <p>Diameter: {foundPlanet.diameter}</p>
        <p>Length of Day: {foundPlanet.lengthOfDay} hours</p>
      </div>
    )
  }
  ```
</details>

<br>

<details>
  <summary>Challenge #6</summary>

  ```js
  renderPlanets() {
    const planetsWRings = planetData.filter((planet) => {
      return planet.ringSystem === true;
    });

    return planetsWRings.map((planet) => {
      return (
        <div>
          <h4>{planet.name}</h4>
          <p>Diameter: {planet.diameter}</p>
          <p>Length Of Day: {planet.lengthOfDay}</p>
        </div>
      )
    });
  }
  ```
</details>

<br>

<details>
  <summary>Challenge #7</summary>

  ```js
  renderPlanets() {
    const jupiter = planetData.find((planet) => planet.name === 'Jupiter');

    return jupiter.moons.map((moon) => {
      return <li>{moon}</li>;
    });
  }
  ```
</details>

<br>