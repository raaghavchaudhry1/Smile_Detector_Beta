# SmileDetector
<!-- https://utmist.gitlab.io/projects/smiledetector/
 -->
<!-- # [![Contributors][contributors-shield]][contributors-url] -->

[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="https://utmist.gitlab.io/projects/smiledetector/smile_hu1f2c665efb998e6a3fe75cbd3952c625_43861_600x0_resize_box_2.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">SmileDetector: Detecting and Rating Smiles</h3>

  <p align="center">
    SmileDetector is a web application that uses machine learning to detect and rate smiles. SmileDetector will calculate your ideal smile based off of your facial structure so that you can smile better in pictures. Machine learning accurately scans and maps facial vectors to your face to measure and track your facial structure and movements. After using SmileDetector you will never have to worry about posing for photos again. Soon you will be able to smile perfectly the second you see a camera.
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
<!-- 
[![Product Name Screen Shot][product-screenshot]](https://example.com)

Here's a blank template to get started: To avoid retyping too much info. Do a search and replace with your text editor for the following: `github_username`, `repo_name`, `twitter_handle`, `linkedin_username`, `email`, `email_client`, `project_title`, `project_description` -->

<!-- <p align="right">(<a href="#top">back to top</a>)</p>
 -->


### Built With

* [OpenCV](https://opencv.org/)
* [scikit-learn](https://scikit-learn.org/stable/)
* [tkinter](https://docs.python.org/3/library/tkinter.html)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

You will need to install librarires that are used in this project using:
* pip
  ```sh
  pip3 install LIBRARY_NAME
  ```

### Installation

1. Clone the repo
   ```sh
   git@github.com:NoahCristino/SmileDetector.git
   ```
3. Install NPM packages
   ```sh
   pip3 install LIBRARY_NAME
   ```
4. Run `GUI.py`
   ```js
   python3 GUI.py
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

### Files

**build_data.py** - generates pandas dataframe using images in genki folder

**facePoints.py** - library containing functions:

* *predict*: makes prediction with model

* *localize*: rotates detected points on face to ensure correct orientation and scales based on image size

* *image_score*: generates list of points on mouth

**facial.py** - remove and incorporate into GUI (live prediction on webcam)

**GUI.py** - runs live webcam feed with GUI

**mainMenu.py** - main menu that displays credits and calls GUI (should we merge GUI and mainMenu into 1 file?)

**smileload.py** - takes in 1 argument which is an image file to run model prediction on

**smilemodel.py** - trains model

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
<!-- ## Roadmap

- [] Feature 1
- [] Feature 2
- [] Feature 3
    - [] Nested Feature

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p> -->



<!-- CONTRIBUTING -->
<!-- ## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>
 -->


<!-- LICENSE -->
<!-- ## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>
 -->


<!-- CONTACT -->
## Contact

Noah Cristino - noahcristino@yahoo.com

Project Link: [https://github.com/NoahCristino/SmileDetector](https://github.com/NoahCristino/SmileDetector)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
<!-- ## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#top">back to top</a>)</p> -->



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/NoahCristino/SmileDetector/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://utmist.gitlab.io/images/logos/blueside.svg
[linkedin-url]: https://utmist.gitlab.io/projects/smiledetector/
[product-screenshot]: images/screenshot.png
