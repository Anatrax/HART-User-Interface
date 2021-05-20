<!-- GitHub Badges/Shields -->
<!-- See https://shields.io/ for more options. -->
[![CI/CD][cicd-shield]][cicd-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]
-----
<br />
<p align="center">
  <!-- PROJECT LOGO -->
  <a href="https://osuaiaa.com/hart">
	<img src="https://images.squarespace-cdn.com/content/v1/5a19a459e5dd5b3614fc8595/1518733757123-JZ5199GBQVQOEJBC9VKR/ke17ZwdGBToddI8pDm48kOx9thYkxoPEJMHoJ7vUPbh7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QHyNOqBUUEtDDsRWrJLTmS0k9nmfOWkBD2X4dgpGrpWVYQT8AbCbINUUJycgJH0K3YOIy-qewO29_jEB_UvA_/HARTlogo.jpg" width="200px" height="auto"/>
  </a>

  <!-- PROJECT TITLE -->
  <h1 align="center">OSU HART Launch Controller</h1>

  <p align="center">
    <!-- SHORT PROJECT DESCRIPTION -->
    User interface for the OSU HART Launch System
    <br />
    <!-- LINK TO DOCUMENTATION -->
    <a href="https://hart-avionics.github.io/osu-hart-user-interface/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <!-- LINK TO DEMO
    <a href="INSERT LINK TO DEMO HERE">View Demo</a>
    · -->
    <!-- LINK TO ISSUES -->
    <a href="https://github.com/HART-Avionics/osu-hart-user-interface/issues">Report Bug</a>
    ·
    <!-- LINK TO ISSUES -->
    <a href="https://github.com/HART-Avionics/osu-hart-user-interface/issues">Request Feature</a>
  </p>
</p>

Table of Contents
---------------------
- [About the Project](#about-the-project)
  - [Built with](#about-the-project-built-with)
- [Getting Started](#getting-started)
  - [Parts List](#getting-started-parts-list)
  - [Assembling the Controller](#getting-started-assembling)
- [Using the Controller](#usage)
- [Roadmap](#roadmap)
<!--
- [FAQ](#faq)
-->
- [Contributing](#contributing)
- [License](#license)
- [Contacts](#contacts)
- [Support the Project](#donate)
<!--
- [Acknowledgements](#acknowledgements)
-->

<a name="about-the-project"></a>
About the Project
---------------------
<!-- Description of the project and it's intended purpose or origin story. -->
The launch controller is the user interface of the Launch System. It is used to send the launch signal to the launch ignition box, thereby triggering the rocket booster ignition from a safe distance.

<a name="about-the-project-built-with"></a>
### Built with
<!-- This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the Acknowledgements section. Here are a few examples.
- [Sphinx](https://www.sphinx-doc.org/en/master/usage/installation.html) documentation generator
- [TexLive](https://www.tug.org/texlive/)
-->
- Teensy
- XBee

<a name="getting-started"></a>
Getting Started
---------------------
<!-- This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple example steps. -->

<a name="getting-started-parts-list"></a>
### Parts List
- Electrical wire
- Compact 12v battery
- Teensy 4.0
- Buck boost converter
- Key-operated switch
- Dual-position selector switch
- Big red button
- Green indicator LED
- Yellow indicator LED
- Red indicator LED
- Xbee Pro S3B
- 3D-printed enclosure
  - Enclosure
  - Lid
  - Corners (x4)
  - Screws (x4)

<a name="getting-started-assembling"></a>
### Assembling the Controller
1. Print the enclosure
2. Glue the corners onto the enclosure
    ![Enclosure corner placement][corner-placement]
2. Wire electronic components together according to the wiring diagram
    ![Wiring diagram][wiring-diagram]
3. Put the electronics in the enclosure
4. Screw the lid onto the enclosure

<a name="usage"></a>
Using the Controller
---------------------
1. Make sure that the launch ignition box is armed & ready and everyone is a safe distance away from the launch pad
2. Power on the launch controller by turning the key switch in the clockwise direction
    ![Key-operated power switch][powering-on]
3. Turn the black arming switch to the upward position in order to arm the system; once a connection to the launch ignition box has been established, the safety siren on the launch ignition box should activate
    ![Dual-position arming selector switch in vertical position][arming]
4. Press the large red button to launch the rocket when ready
    ![Dual-position arming selector switch in vertical position][launching]

<a name="roadmap"></a>
Roadmap
----------
See the [open issues][issues-url] for a list of proposed features (and known issues).

<!--
<a name="faq"></a>
FAQ
----
-->

<a name="contributing"></a>
Contributing
---------------
Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the project
2. Create your feature branch (`git checkout -b username/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin username/amazing-feature`)
5. Open a pull request onto the `develop` branch of the official repository

<a name="license"></a>
License
-----------
Distributed under the GNU Public License. See [`LICENSE`][license] for more information.

<a name="contacts"></a>
Contacts
-----------
<!-- Your Name - @your_twitter - example@example.com -->
**Maintainer**: Samuel D. Villegas - villegsa@oregonstate.edu

<a name="donate"></a>
Support the Project
--------------------
[Donate to HART][donate-url]
<!--
<a name="acknowledgements"></a>
Acknowledgements
-----------------
- [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
- [Img Shields](https://shields.io)
- [Choose an Open Source License](https://choosealicense.com)
- [GitHub Pages](https://pages.github.com)
- [Animate.css](https://daneden.github.io/animate.css)
- [Loaders.css](https://connoratherton.com/loaders)
- [Slick Carousel](https://kenwheeler.github.io/slick)
- [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
- [Sticky Kit](http://leafo.net/sticky-kit)
- [JVectorMap](http://jvectormap.com)
- [Font Awesome](https://fontawesome.com)
-->
<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[cicd-shield]: https://github.com/HART-Avionics/osu-hart-user-interface/workflows/CI/CD/badge.svg?branch=develop
[cicd-url]: https://github.com/HART-Avionics/docs/actions "CI/CD"
[contributors-shield]: https://img.shields.io/github/contributors/HART-Avionics/osu-hart-user-interface
[contributors-url]: https://github.com/HART-Avionics/osu-hart-user-interface/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/HART-Avionics/osu-hart-user-interface
[forks-url]: https://github.com/HART-Avionics/osu-hart-user-interface/network/members
[stars-shield]: https://img.shields.io/github/stars/HART-Avionics/osu-hart-user-interface
[stars-url]: https://github.com/HART-Avionics/osu-hart-user-interface/stargazers
[issues-shield]: https://img.shields.io/github/issues/HART-Avionics/osu-hart-user-interface
[issues-url]: https://github.com/HART-Avionics/osu-hart-user-interface/issues
[license-shield]: https://img.shields.io/github/license/HART-Avionics/osu-hart-user-interface
[license-url]: https://github.com/HART-Avionics/osu-hart-user-interface/blob/main/LICENSE
[corner-placement]: ./docs/images/corner_placement.png "Enclosure corner placement"
[wiring-diagram]: ./docs/images/wiring_diagram.png "Wiring diagram"
[powering-on]: ./docs/images/power_on.png
[arming]: ./docs/images/arming.png
[launching]: ./docs/images/launching.png
[license]: ./LICENSE "GNU Public License"
[donate-url]: https://osuaiaa.com/donate
