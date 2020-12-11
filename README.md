<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
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
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Best-README-Template</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
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
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

There are many great README templates available on GitHub, however, I didn't find one that really suit my needs so I created this enhanced one. I want to create a README template so amazing that it'll be the last one you ever need -- I think this is it.

Here's why:
* Your time should be focused on creating something amazing. A project that solves a problem and helps others
* You shouldn't be doing the same tasks over and over like creating a README from scratch
* You should element DRY principles to the rest of your life :smile:

Of course, no one template will serve all projects since your needs may be different. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue. Thanks to all the people have have contributed to expanding this template!

A list of commonly used resources that I find helpful are listed in the acknowledgements.

### Built With

This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [C#(Windows Forms App(.NET Framework)](https://dotnet.microsoft.com/)
* [YoutubeDataAPI](https://developers.google.com/youtube/v3)



<!-- GETTING STARTED -->
## Getting Started

프로젝트를 로컬저장소에 다운받아 설정하는 방법에 대한 지침을 제공하는 방법입니다.
프로젝트를 실행하려면 다음 단계들을 따라해주세요.

### Prerequisites

프로젝트를 실행시키기 위해 필요한 소프트웨어 및 설치방법을 알려주는 예시입니다.

1. 비쥬얼 스튜디오를 설치합니다. 이 프로젝트는 2019버전을 사용하였습니다.
* Visual Studio 2019
  ```sh
  [https://visualstudio.microsoft.com/ko/vs/](https://visualstudio.microsoft.com/ko/vs/)
  ```
2. VS에서 '추가 도구 및 기능설치' 를 누르고 Windows Forms App(.NET Framework) 템플릿을 설치합니다.

### Installation

1. 본인의 ' Youtube API KEY ' 를 발급받습니다. [https://console.developers.google.com](https://console.developers.google.com)
2. repo를 Clone 합니다.
 ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Youtube-Crawler 폴더 안의 Like_Youtube.sln 을 실행시킵니다. 
4. API 패키지를 설치합니다.
*VS에서 Nuget 패키지 관리자 >> 패키지 관리자 콘솔(Package Manager Console)
  ```sh
  install-package Google.APIs
  install-package Google.APIs.YouTube.v3
  ```
* 4번째 단계는 Youtube Data API를 사용하기 위해 설치하는 패키지입니다. 위 프로젝트에는 패키지가 이미 있기에 별도의 설치가 필요없으며 차후 버전의 문제나 별도의 작업을 하실 경우 참고하여 설치 해주세요.  
5. Form1의 176, 366번째 줄에 본인의 API 키를 넣습니다.
 ```
   ApiKey=" put your API Key "
   ```

<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

여러분의 기여는 오픈 소스 커뮤니티를 윤택하고 활력 있는 배움과 영감의 장소로 만들어 줍니다. 모든 의견은 항상 **감사하게** 받겠습니다.

1. 프로젝트를 Fork 합니다.
2. master 기반으로 브랜치를 만듭니다.
3. 수정하여 Commit 합니다.
4. 브랜치에 Push 합니다.
5. Pull Request를 생성합니다.



<!-- LICENSE -->
## License

README.md는 오픈소스를 활용한 것으로 MIT 라이선스에 따라 배포됩니다. 자세한 내용은 LICENSE를 참조하세요.

<!-- CONTACT -->
## Contact

정희철 - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/PortfolioImg1.png
