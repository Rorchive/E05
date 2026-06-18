<h1 align="center">E05 - Motor Driver</h1>

<p align="center">
    <a href="#"><img alt="Static Badge" src="https://img.shields.io/badge/status-testing-yellow"></a>
    <a href="https://github.com/Rorchive/E05/releases"><img alt="GitHub Release" src="https://img.shields.io/github/v/release/Rorchive/E05"></a>
    <a href="https://github.com/Rorchive/E05/issues"><img alt="GitHub Issues or Pull Requests" src="https://img.shields.io/github/issues/Rorchive/E05"></a>
    <a href="https://github.com/Rorchive/E05/pulls"><img alt="GitHub Issues or Pull Requests" src="https://img.shields.io/github/issues-pr/Rorchive/E05"></a>
    <a href="https://github.com/Rorchive/E05/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/Rorchive/E05"></a>
</p>

<p align="center">
    <a href="#overview">Overview</a> •
    <a href="#repository-organization">Repository Organization</a> •
    <a href="#releases">Releases</a> •
    <a href="#license">License</a>
</p>


## Overview
This project involves the development of a DC Motor Driver module tailored for the E05 (Transistorized Analog Electronics) course at Inatel. The system is engineered to handle electromechanical switching using a purely analog architecture, providing robust motor control based on a BC547 NPN transistor acting as a driver for a 5V SPDT relay (Songle SRD series). The hardware design incorporates inductive spike protection via a 1N5408 flyback diode, input state stabilization through a push-button with a pull-down network, and real-time visual feedback via an LED indicator.

<p align="center">
    <img src="docs/pictures/PCB-render.png" width="400">
</p>

## Repository Organization

* `docs`: Technical documentation and datasheets.
* `hardware`: Core hardware files.
    * `3D`: 3D models (.step).
    * `Fabrication`: BOM and Gerber files for JLCPCB manufacturing.
    * `PCB`: KiCad schematics and layout design.

## Releases

<table>
  <thead>
    <tr>
      <th>Render</th>
      <th>Board Name</th>
      <th>Status</th>
      <th>Latest Release</th>
      <th>Date</th>
      <th>Datasheet</th>
      <th>BOM</th>
      <th>Ordering Info</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img style="max-width: 200px;" src="docs/pictures/PCB-render.png" alt="render"/></td>
      <td>Motor Driver v1</td>
      <td>🧪 Testing</td>
      <td><a href="https://github.com/Rorchive/E05/releases/tag/v1r1">v1r1</a></td>
      <td>2026-06-18</td>
      <td></td>
      <td>No</td>
      <td><a href="hardware/Fabrication/GERBER-Transistor_Driver.zip">GERBER</a> (JLCPCB)</td>
    </tr>
  </tbody>
</table>

## License

This project is licensed under the weakly-reciprocal **[CERN-OHL-W-2.0](LICENSE)** open-hardware license. You are free to modify and distribute these files, provided downstream hardware design modifications remain under the same terms.

---

<br/>

<div align="center">
  <img src="https://raw.githubusercontent.com/Rorchive/.github/main/assets/logo_text.png" alt="Rorchive Logo" style="width: 256px;"/>
</div>

<div align="center">
<sub>📜 Este projeto faz parte do <strong><a href="https://github.com/Rorchive">Rorchive</a></strong>, meu arquivo pessoal de atividades e cursos desenvolvidos durante a graduação no <strong>Inatel</strong>.</sub>

  <sub>Construído com ❤️ por <a href="https://github.com/RodrigoCAndrade">Rodrigo Andrade</a></sub>
</div>