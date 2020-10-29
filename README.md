<p align="center">
  <h3 align="center">Lotus Notes/Domino V9 to Cloudant (Bluemix) HTTP Requests</h3>

  <p align="center">
    This open source utility describes the solution to send HTTP GET and PUT requests from IBM Notes/Domino to Cloudant db. This will be useful for teams who are planning to re-write their Lotus Notes applications to modern technology (NodeJs, Angular etc) and deploy in Bluemix.
    <br />
    <a href="https://github.com/IBM/Domino-to-Cloudant-HTTP-Requests"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/IBM/Domino-to-Cloudant-HTTP-Requests">Scope</a>
    ·
    <a href="https://github.com/IBM/Domino-to-Cloudant-HTTP-Requests/issues">Report Bug</a>
    ·
    <a href="https://github.com/IBM/Domino-to-Cloudant-HTTP-Requests/issues">Request Feature</a>
  </p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
* [Instruction and Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

IBM introduced CORS supports for Domino REST API in Domino V10. Domino versions prior to V10 (V9.0.1 and above) don't have CORS support and we can not send Cross-Origin REST requests from Domino v9.0 (Not in easy way at least).  So it becomes very challenging to interact with Cloudant from Lotus Notes applications. You may have a need to get data from Cloudant and store it in Lotus Notes database, but without CORS support sending a REST request is very difficult.

This solution has a Java Agent that you can run from your Lotus Notes application. This agent can send HTTP GET and PUT requests to Cloudant, get JSON response and then create document in your Lotus Notes database. You can modify this agent to send UPDATE and DELETE requests as well. Included "java-json" jar file is used to convert JSON to Java Object and vice versa. 

### Built With

* Lotus Notes V9.0.1
* Lotus Notes Java Agent
* Cloudant



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

<!-- USAGE EXAMPLES -->
## Instruction and Usage

Please refer to the [Documentation][documentation-file]. This documentation explains in detail how you can setup your domino environment, jar files, Java Agent and how you can run the agent. This also has the Java Agent code.
<br /><br />
<b>As Java Agents can only be created and run from Lotus Notes, I have attached the code sample in the documentation.</b>



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/IBM/Domino-to-Cloudant-HTTP-Requests/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

This code pattern is licensed under the Apache Software License, Version 2.  Separate third party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1 (DCO)](https://developercertificate.org/) and the [Apache Software License, Version 2](https://www.apache.org/licenses/LICENSE-2.0.txt).

[Apache Software License (ASL) FAQ](https://www.apache.org/foundation/license-faq.html#WhatDoesItMEAN)



<!-- CONTACT -->
## Contact

Kirti Jha - kirtijha@in.ibm.com

Project Link: [https://github.com/IBM/Domino-to-Cloudant-HTTP-Requests](https://github.com/IBM/Domino-to-Cloudant-HTTP-Requests)







<!-- MARKDOWN LINKS & IMAGES -->
[documentation-file]: documentation/Domino%20to%20Cloudant%20HTTP