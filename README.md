<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** zayanimed97, Eden-ai, twitter_handle, zayanimed97@gmail.com, Eden AI, project_description
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/zayanimed97/Eden-ai">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Eden AI</h3>

  <p align="center">
    Eden AI simplifies the use and integration of AI technologies by providing a unique API connected to the best AI engines and combined with a powerful management platform
    <br />
    <a href="https://api.edenai.run/v1/redoc/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://www.edenai.co/">View Demo</a>
    ·
    <a href="https://github.com/zayanimed97/Eden-ai/issues">Report Bug</a>
    ·
    <a href="https://github.com/zayanimed97/Eden-ai/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* Composer(https://getcomposer.org/download/)

### Installation

1. Install Composer packages
   ```sh
    composer require eden-ai/php-sdk
   ```
2. Create an account at https://app.edenai.run/user/register
   
   
3. Get your API KEY


<!-- USAGE EXAMPLES -->
## Usage

You can use this package by initiating your desired class using the generate API KEY from your account just like the example:

```PHP
  require_once '../vendor/autoload.php';

  use eden-ai/Text;
  $text = new Text("API_KEY");
  $output = $text->keywordExtraction(string $text[, array $keywords_to_find][, array $providers ][, string $language])
```
<table>
    <tr>
        <th>Class</th>
        <th>Methods</th>
        <th>Parameters</th>
    </tr>
    <tr>
        <td rowspan='15' colspan='1'>Text</td>
        <td rowspan='4' colspan="1">keywordExtraction()</td>
        <td>String $text (required)</td>
    </tr>
    <tr>
        <td> Array $keywords_to_find (optional) </td>
    </tr>
    <tr>
        <td> Array $providers (optional) </td>
    </tr>
    <tr>
        <td> String $language (optional) </td>
    </tr>
    <tr>
        <td rowspan='4' colspan="1">namedEntityRecognition()</td>
        <td>String $text (required)</td>
    </tr>
    <tr>
        <td> Array $entities_to_find (optional) </td>
    </tr>
    <tr>
        <td> Array $providers (optional) </td>
    </tr>
    <tr>
        <td> String $language (optional) </td>
    </tr>
    <tr>
        <td rowspan='4' colspan="1">sentimentAnalysis()</td>
        <td>String $text (required)</td>
    </tr>
    <tr>
        <td> Array $sentiments_to_find (optional) </td>
    </tr>
    <tr>
        <td> Array $providers (optional) </td>
    </tr>
    <tr>
        <td> String $language (optional) </td>
    </tr>
    <tr>
        <td rowspan='3' colspan="1">syntaxAnalysis()</td>
        <td>String $text (required)</td>
    </tr>
    <tr>
        <td> Array $providers (optional) </td>
    </tr>
    <tr>
        <td> String $language (optional) </td>
    </tr>
</table>  



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/zayanimed97/Eden-ai/issues) for a list of proposed features (and known issues).



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

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - zayanimed97@gmail.com

Project Link: [https://github.com/zayanimed97/Eden-ai](https://github.com/zayanimed97/Eden-ai)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* []()
* []()
* []()





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/zayanimed97/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/zayanimed97/Eden-ai/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/zayanimed97/repo.svg?style=for-the-badge
[forks-url]: https://github.com/zayanimed97/Eden-ai/network/members
[stars-shield]: https://img.shields.io/github/stars/zayanimed97/repo.svg?style=for-the-badge
[stars-url]: https://github.com/zayanimed97/Eden-ai/stargazers
[issues-shield]: https://img.shields.io/github/issues/zayanimed97/repo.svg?style=for-the-badge
[issues-url]: https://github.com/zayanimed97/Eden-ai/issues
[license-shield]: https://img.shields.io/github/license/zayanimed97/repo.svg?style=for-the-badge
[license-url]: https://github.com/zayanimed97/Eden-ai/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/zayanimed97
