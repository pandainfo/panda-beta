<p align="center">
  <a href="https://github.com/pandainfo/panda-beta">
    <img alt="Panda" src="https://avatars2.githubusercontent.com/u/48161788?s=200&v=4" height="100">
  </a>
</p>

<p align="center">
  <strong>stay radical!  🐼  read books!  📚</strong>
  <br />
  Built in Vienna with ❤️
</p>

> **ATTENTION: This project is still in beta stage, so things are open for change.**

<!--
[![AGPL-3.0 License](https://flat.badgen.net/github/license/pandainfo/panda-beta)](COPYING)
[![Latest Version](https://flat.badgen.net/packagist/v/pandainfo/panda-beta)](https://packagist.org/packages/pandainfo/panda-beta)
[![Build Status](https://flat.badgen.net/github/checks/pandainfo/panda-beta?label=build&icon=github)](https://github.com/pandainfo/panda-beta/actions)
[![Monthly Downloads](https://flat.badgen.net/packagist/dm/pandainfo/panda-beta)](https://packagist.org/packages/pandainfo/panda-beta/stats)
 -->
[![PHP Composer](https://github.com/pandainfo/panda-beta/workflows/PHP%20Composer/badge.svg)](https://github.com/pandainfo/panda-beta/actions?query=workflow%3A%22PHP+Composer%22)
[![Follow @redtux](https://flat.badgen.net//twitter/follow/redtux)](https://twitter.com/redtux)

# Welcome to Panda

**[Panda](https://github.com/pandainfo/panda)** aims to provide a modern new generation CRM, ERP &
CMS with [ONIX] and [VLB] support for selling, merchandising and searching books and digital media.

[ONIX]: https://en.wikipedia.org/wiki/ONIX_for_Books "ONIX for Books on Wikipedia"
[VLB]: https://de.wikipedia.org/wiki/Verzeichnis_Lieferbarer_Bücher "Verzeichnis Lieferbarer Bücher on Wikipedia"

> **Powered by**

* [![Build Status](https://img.shields.io/github/stars/roots/bedrock.svg?style=flat-square)](https://github.com/roots/bedrock) [**Bedrock**](https://roots.io/bedrock/)
* [![Build Status](https://img.shields.io/github/stars/WordPress/WordPress.svg?style=flat-square)](https://github.com/WordPress/WordPress) [**WordPress Core**](https://make.wordpress.org/core/components/)

For full documentation visit the [docs] pages.

[docs]: https://pandainfo.github.io/community/ "Panda Docs"

---

> **Table of contents**

1. [About](#about)
2. [Contributing](#contributing)
3. [TODOs](#todos)
4. [Authors](#authors)
5. [Licensing](#licensing)

## About

> **PANDA – NEXT GENERATION E-COMMERCE PLATFORM**

Panda integrates several components in one system.

* [ ] **eCommerce:** Buying and searching books on the Panda Store 2.0
* [ ] **OMS:** Making your customers happy with Panda Order Management
* [ ] **DMS:** Organizing all paperwork with Panda Document Management
* [ ] **Website Builder:** Creating secure and fast Panda Landing Pages in static HTML and JS
* [ ] **CMS:** Writing publications in teams via Panda Editorial Board & Panda's Site Creator
* [ ] **ActivityPub:** Running booksellers associations using Panda Fediverse Social Networks
* [ ] **Library:** Organizing titles and bibliographies in the Panda Book Catalog with ONIX & OPAC
* [ ] **VLB:** Support for the Verzeichnis Lieferbarer Bücher (VLB) or Directory of Available Books
* [ ] **Prices:** Keeping track of price changes through the VLB Price Reference Database for Austria and Germany
* [ ] **Search:** Integration of [buchhandel.de], the public VLB search platform for books in Austria and Germany
* [ ] **SCM:** Planning warehouse logistics with VLB and dispatch lists through the Panda Supply Chain Management
* [ ] **CRM:** Simplifying online marketing, newsletter administration & guest care via Panda Customer Management
* [ ] **Accounting:** Maintaining control over all business assets and finances with the [Panda Accounting Suite]
* [ ] **Customizations:** Connecting APIs with [Pipedream] and fulfilling your wishes with Panda Custom Solutions
* [ ] **ERP:** Controlling the warehouse with Panda Merchandise Management and Panda Enterprise Resource Planning
* [ ] **HRM:** Coordinating working hours, shifts, and responsibilities of co-workers & teams through Panda Staff
* [ ] **Panda Stack:** Deploying Production (live), Staging (beta) and Testing Environments for CI/CD integration
* [ ] **Support:** Assisting with Online Discussion Boards, Documentation & Tutorials, Live Trainings or Webinars

[buchhandel.de]: https://www.buchhandel.de/suche "VLB Public Research Platform"
[Panda Accounting Suite]: https://www.invoiceninja.org/ "Powered by Invoice Ninja"
[Pipedream]: https://github.com/PipedreamHQ/pipedream#readme "Pipedream Integration Platform"

## Contributing

All contributions are beautiful! We welcome all kind of assistance.

The **Panda Platform** is being primarily developed and maintained
by Pablo Hörtner for Panda IT Solutions, together with [argo coop]
- and with contributions from the community. Just join us now! :-)

Like many other projects nowadays Panda IT Solutions and argo have
a [Code of Conduct] (CoC) comparable to the old days' [Netiquette].

The project is licensed under the [GNU AGPL][agpl] (Version 3.0 or
later). Code may only be used in compliance with this license, and
we kindly ask you to read both the AGPL license and the CoC before
contributing to this project. For details [see below](#️licensing).

**Happy hacking!** 💜🤓

[code of conduct]: code_of_conduct.md "Contributor Covenant Code of Conduct"
[Netiquette]: https://tools.ietf.org/html/rfc1855 "Netiquette Guidelines from October 1995"
[agpl]: https://www.gnu.org/licenses/agpl-3.0.html "GNU Affero General Public License"
[argo coop]: https://argo.coop "argo IT eG · Austrian IT Coop"

## TODOs

* [ ] Add features described above as plugins and via WP-CLI
  * [x] Static Site Builder
  * [ ] ActivityPub
  * [x] CMS Creator
  * [x] WooCommerce
  * [x] ONIX Import
  * [x] CRM
  * [x] Newsletter management
  * [x] ERP
  * [ ] DMS
  * [ ] Accounting
  * [ ] HRM
* [x] Rename `README.md` title to **NEXT GENERATION E-COMMERCE PLATFORM**
  * [ ] Explain markdown and new generation e-commerce
  * [ ] Explain separation of content and presentation
  * [ ] Explain micro-services and dependency management
  * [ ] Explain automation, clouds, CI/CD, CDN, etc.
* [x] Move Panda Docs to <https://github.com/pandainfo/community>
* [ ] Include Panda Core docs
* [ ] Add `.env` to GitHub secrets
* [x] Create WP instances
  * [ ] https://radicalbookstore.name/
  * [ ] https://shop.radicalbookstore.com/
* [x] Create deploy GitHub Actions for
  * [ ] development
  * [ ] staging
  * [ ] production
* [x] Deploy to Hetzner via sftp

## Authors

* **Pablo Hörtner** - _Initial work_ - [🐼 Team panda!](https://github.com/orgs/pandainfo/teams/panda)

See also the [AUTHORS.md](AUTHORS.md) file and the [full list of contributors](https://github.com/pandainfo/panda-beta/contributors) who participated in this project.

## Licensing

    PANDA – NEXT GENERATION E-COMMERCE PLATFORM
    COPYRIGHT (c) 2022  PABLO HÖRTNER <REDTUX@PM.ME>

Unless explicitly noted otherwise, all the content on this site is released under the following terms.
For further information see [copyright]. For other licenses of third parties see this [NOTICE](NOTICE).

[copyright] https://pandainfo.github.io/community/copyright/ "Panda Copyright"

**Panda** is Free Software. You can redistribute it and/or modify it under the terms of
the **GNU Affero General Public License** as published by the Free Software Foundation,
either version 3 of the License, or at your option any later version: AGPL-3.0-or-later

    This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY;
    without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
    See the GNU Affero General Public License for more details.

You may obtain a copy of the License [here](COPYING) or at

    https://www.gnu.org/licenses/agpl-3.0.html
