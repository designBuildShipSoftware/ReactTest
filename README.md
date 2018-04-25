# ReactTest

import React, { Component } from 'react';

class Projects extends Component {
  render() {
      console.log(this.props);
    return (
      <div className="Comp1">
       My Projects.{"\n"}
       {this.props.test}
      </div>
    );
  }
}

export default Projects;


import React, { Component } from 'react';
import Projects from './Components/Comp1';

class App extends Component {
  render() {
    return (
      <div className="App">
       Hong's React Project
       <Comp1 test="This is a test property" />
      </div>
    );
  }
}

export default App;
