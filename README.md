[![Linux build](https://github.com/Open-Typer/Open-Typer/actions/workflows/linux-build.yml/badge.svg?event=push)](https://github.com/Open-Typer/Open-Typer/actions/workflows/linux-build.yml)
[![macOS Build](https://github.com/Open-Typer/Open-Typer/actions/workflows/macos-build.yml/badge.svg?event=push)](https://github.com/Open-Typer/Open-Typer/actions/workflows/macos-build.yml)
[![Windows build](https://github.com/Open-Typer/Open-Typer/actions/workflows/windows-build.yml/badge.svg?event=push)](https://github.com/Open-Typer/Open-Typer/actions/workflows/windows-build.yml)
[![WebAssembly build](https://github.com/Open-Typer/Open-Typer/actions/workflows/wasm-build.yml/badge.svg?event=push)](https://github.com/Open-Typer/Open-Typer/actions/workflows/wasm-build.yml)
[![Snap package](https://github.com/Open-Typer/Open-Typer/actions/workflows/snap.yml/badge.svg?event=push)](https://github.com/Open-Typer/Open-Typer/actions/workflows/snap.yml)

<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![GPLv3 License][license-shield]][license-url]

<br />
<div align="center">
  <a href="https://github.com/vetrivln/tamil99/">
    <img src="res/linux-release/usr/share/pixmaps/open-typer.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Open-Typer Tamil99</h3>

  <p align="center">
    Free and open source typing tutor with Tamil99 keyboard support
    <br />
    <a href="https://open-typer.github.io"><strong>Explore the original docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/vetrivln/tamil99/issues">Report Bug</a>
    ·
    <a href="https://github.com/vetrivln/tamil99/issues">Request Feature</a>
  </p>
</div>

---

## About The Project

[![Open-Typer screenshot][product-screenshot]](https://open-typer.github.io)

This project is a fork of **Open-Typer**, extended with support for the **Tamil99 keyboard layout**, a standard widely used for typing in Tamil.

### ✨ Key Features
- Support for **Tamil99 keyboard layout**
- Auto-generated typing lessons adapted for Tamil characters
- Cross-platform: Windows, Linux, and macOS
- Clean and simple UI powered by Qt

Open-Typer aims to make learning touch typing easier, and this fork expands that goal to Tamil language users.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

### Built With

<a href="https://www.qt.io"><img src="https://img.shields.io/badge/Qt-000000?style=flat-square&logo=qt&logoColor=qt" height="50"></a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Getting Started

### Building

Follow the original build instructions:
https://open-typer.github.io/docs/md_docs_data_pages_Build_instructions.html

### Installation

See:
https://open-typer.github.io/docs/index.html

> Note: Tamil99 support is included by default in this fork.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Roadmap

- [x] Tamil99 keyboard support
- [ ] Tamil lesson packs
- [ ] UI localization (Tamil language interface)
- [ ] Additional Indian language layouts

See the issues page for more ideas.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Contributing

Contributions are welcome, especially for:
- Improving Tamil typing lessons
- Fixing layout mapping issues
- Adding localization support

Steps:

1. Fork the Project  
2. Create your Feature Branch (`git checkout -b feature/TamilImprovement`)  
3. Commit your Changes (`git commit -m 'Improve Tamil99 support'`)  
4. Push to the Branch (`git push origin feature/TamilImprovement`)  
5. Open a Pull Request  

### Code Style

Install clang-format:

`sudo apt-get install clang-format`

Run:

`clang-format -i src/*.cpp`

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## License

Distributed under the GNU General Public License v3.0.

See `LICENSE` for more information.

---

## Acknowledgements

- Original project: https://github.com/Open-Typer/Open-Typer
- Tamil99 layout standard contributors

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- MARKDOWN LINKS -->
[contributors-shield]: https://img.shields.io/github/contributors/vetrivln/tamil99.svg?style=for-the-badge
[contributors-url]: https://github.com/vetrivln/tamil99/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/vetrivln/tamil99.svg?style=for-the-badge
[forks-url]: https://github.com/vetrivln/tamil99/network/members
[stars-shield]: https://img.shields.io/github/stars/vetrivln/tamil99.svg?style=for-the-badge
[stars-url]: https://github.com/vetrivln/tamil99/stargazers
[issues-shield]: https://img.shields.io/github/issues/vetrivln/tamil99.svg?style=for-the-badge
[issues-url]: https://github.com/vetrivln/tamil99/issues
[license-shield]: https://img.shields.io/github/license/vetrivln/tamil99.svg?style=for-the-badge
[license-url]: https://github.com/vetrivln/tamil99/blob/master/LICENSE.txt
[product-screenshot]: docs-data/res/images/main_window_light.png
