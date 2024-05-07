# Docker test Hello World

This is the outcome of a tutorial on youtube. video link: https://www.youtube.com/watch?v=twv_kCq693o&t=603s&ab_channel=FancyGUI

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

Instructions on how to install and set up your project.

## Usage

to update changes use
docker build . -t dash:0.0.1
This updates the build and tags it with the name "dash" and version "0.0.1"
<br>
use this to run 
docker run -p 5000:5000 dash:0.0.1
<br>
Also, for interactive bash mode use
docker run -it -p 5000:5000 dash:0.0.1 sh
this opens a terminal in the container
## Contributing

Guidelines on how others can contribute to your project.

## License

Information about the license for your project.