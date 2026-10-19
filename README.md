<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />
<div align="center">
  <a href="https://github.com/Elouahabi-Naoufal/data-warehouse-etl">
    <h3 align="center">Data Warehouse ETL</h3>
  </a>

  <p align="center">
    Planned end-to-end data warehouse: 27 Excel sheets to Snowflake, modelled with SQL and dbt, served in Power BI.
    <br />
    <a href="https://github.com/Elouahabi-Naoufal/data-warehouse-etl"><strong>Explore the repository »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Elouahabi-Naoufal/data-warehouse-etl/issues/new?labels=bug">Report Bug</a>
    &middot;
    <a href="https://github.com/Elouahabi-Naoufal/data-warehouse-etl/issues/new?labels=enhancement">Request Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a>
      <ul><li><a href="#built-with">Built With</a></li></ul>
    </li>
    <li><a href="#getting-started">Getting Started</a>
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
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

This repository is the project space for a fourth-year PFM project at EMSI (semester S2): build a complete data warehouse from 27 operational Excel sheets.

The target design is a classic layered warehouse. Pentaho handles extraction and the initial load, SQL provides the dimensional model, dbt builds and tests the transformation layers, and Power BI serves the reporting marts. The repository is currently a scaffold: it contains only a `.gitkeep` placeholder and no implementation.

* Source: 27 Excel sheets describing the operational system.
* Storage and compute: Snowflake.
* Transformation: SQL modelling plus dbt models and tests.
* Reporting: Power BI dashboards.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

This repository is currently a scaffold, so no stack is wired up yet. The planned stack is:

* [![Pentaho][pentaho-badge]][pentaho-url]
* [![Snowflake][snowflake-badge]][snowflake-url]
* [![dbt][dbt-badge]][dbt-url]
* [![Power BI][powerbi-badge]][powerbi-url]
* [![Excel][excel-badge]][excel-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

The repository has no runnable code yet. The steps below only set up a local checkout for future work.

### Prerequisites

* Git
* The toolchain for the planned stack, installed when the implementation starts.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Elouahabi-Naoufal/data-warehouse-etl.git
   cd data-warehouse-etl
   ```

2. There is nothing to install or start at this stage.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

There is no executable code in this repository. It currently serves as the project space for the
work described above; the usage instructions will be added together with the implementation.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

- [x] Create the repository scaffold.
- [ ] Document the source sheets and their relationships.
- [ ] Implement the Pentaho extraction and load jobs.
- [ ] Write the dimensional model and the Snowflake DDL.
- [ ] Build the dbt staging and mart models, with tests.
- [ ] Connect Power BI to the marts and publish the dashboards.

See the [open issues](https://github.com/Elouahabi-Naoufal/data-warehouse-etl/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Top contributors:

<a href="https://github.com/Elouahabi-Naoufal/data-warehouse-etl/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Elouahabi-Naoufal/data-warehouse-etl" alt="contrib.rocks image" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

This project is not licensed — all rights reserved.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

Naoufal Elouahabi - [LinkedIn](https://www.linkedin.com/in/elouahabi-naoufal/) - elouahabi-naoufal1@gmail.com

Project Link: [https://github.com/Elouahabi-Naoufal/data-warehouse-etl](https://github.com/Elouahabi-Naoufal/data-warehouse-etl)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

* [Snowflake Documentation](https://docs.snowflake.com/)
* [dbt Documentation](https://docs.getdbt.com/)
* [Apache Hop / Pentaho](https://hop.apache.org/)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [Best-README-Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[contributors-shield]: https://img.shields.io/github/contributors/Elouahabi-Naoufal/data-warehouse-etl.svg?style=for-the-badge
[contributors-url]: https://github.com/Elouahabi-Naoufal/data-warehouse-etl/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Elouahabi-Naoufal/data-warehouse-etl.svg?style=for-the-badge
[forks-url]: https://github.com/Elouahabi-Naoufal/data-warehouse-etl/network/members
[stars-shield]: https://img.shields.io/github/stars/Elouahabi-Naoufal/data-warehouse-etl.svg?style=for-the-badge
[stars-url]: https://github.com/Elouahabi-Naoufal/data-warehouse-etl/stargazers
[issues-shield]: https://img.shields.io/github/issues/Elouahabi-Naoufal/data-warehouse-etl.svg?style=for-the-badge
[issues-url]: https://github.com/Elouahabi-Naoufal/data-warehouse-etl/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/elouahabi-naoufal/
[pentaho-badge]: https://img.shields.io/badge/Pentaho-0B6E99?style=for-the-badge&logo=hitachi&logoColor=white
[pentaho-url]: https://www.hitachivantara.com/en-us/products/pentaho-platform.html
[snowflake-badge]: https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white
[snowflake-url]: https://www.snowflake.com/
[dbt-badge]: https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white
[dbt-url]: https://www.getdbt.com/
[powerbi-badge]: https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black
[powerbi-url]: https://powerbi.microsoft.com/
[excel-badge]: https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white
[excel-url]: https://www.microsoft.com/microsoft-365/excel
