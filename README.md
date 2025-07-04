<div align="center">
  <a name="readme-top"></a>
  <a href="https://www.open-c3.online/demo.html" target="_blank"><img src="/c3-front/src/assets/images/open-c3-logo.jpeg" alt="Open-C3" width="100" /></a>
  
## An open-source automated operations platform (DevOps)

[![][license-shield]][license-link]
[![][docs-shield]][docs-link]
[![][deepwiki-shield]][deepwiki-link]
[![][discord-shield]][discord-link]
[![][docker-shield]][docker-link]
[![][github-release-shield]][github-release-link]
[![][github-stars-shield]][github-stars-link]

[English](/README.md) · [中文(简体)](/readmes/README.zh-hans.md) · [中文(繁體)](/readmes/README.zh-hant.md) · [日本語](/readmes/README.ja.md) · [Português (Brasil)](/readmes/README.pt-br.md) · [Español](/readmes/README.es.md) · [Русский](/readmes/README.ru.md) · [한국어](/readmes/README.ko.md)

</div>
<br/>

## What is Open-C3?

Open-C3 is an open-source automated operation and maintenance platform, which includes features such as CMDB, monitoring system, publishing system, work order system, process system, etc., and automatic linkage between various subsystems. It is an integrated automated operation and maintenance platform.

## Quickstart

Prepare a clean Linux Server ( 64 bit, >= 4c8g )

```sh
curl -sSL https://raw.githubusercontent.com/open-c3/open-c3/v2.6.1/Installer/scripts/single.sh | OPENC3VERSION=v2.6.1 bash -s install 10.10.10.10
```

Access Open-C3 in your browser at `http://your-openc3-ip/`
- Username: `open-c3`
- Password: `changeme`

## Screenshots
<table style="border-collapse: collapse; border: 1px solid black;">
  <tr>
    <td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/user-attachments/assets/c3070a34-f1e4-42a9-b240-79056909e00b" alt="Open-C3 CMDB 首页"   /></td>
    <td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/user-attachments/assets/15aff287-4cf1-4eed-8567-65567020df07" alt="Open-C3 CMDB 查看单个资源详情"   /></td>    
  </tr>
  <tr>
    <td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/user-attachments/assets/ac21234e-71ec-49b3-9dd5-c02cf85ed1d8" alt="Open-C3 监控"   /></td>
    <td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/user-attachments/assets/45ba808d-6d89-4aac-b09b-cc6fef4bad33" alt="Open-C3 监控"   /></td>
  </tr>
  <tr>
    <td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/user-attachments/assets/1d52a93f-6b12-46df-ba1c-cad46ea66793" alt="Open-C3 监控"   /></td>     
    <td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/user-attachments/assets/e3f50373-115b-42f4-86a3-9bd5afa085b7" alt="Open-C3 监控"   /></td>
  </tr>
  <tr>
    <td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/user-attachments/assets/584b374f-b3e0-4321-a5a6-96c7be3eeea1" alt="Open-C3 CICD"   /></td>
    <td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/user-attachments/assets/2bc1a7c2-07d9-4cf8-aa35-7e507cee5ef0" alt="Open-C3 CICD"   /></td>
  </tr>
  <tr>
    <td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/user-attachments/assets/fd5a7401-0c4c-4218-b12a-905a59360423" alt="Open-C3 菜单"   /></td>
    <td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/user-attachments/assets/9292eb7a-bba6-4477-af75-8c99f57af410" alt="Open-C3 工单"   /></td>
  </tr>
</table>


## Contributing

Welcome to submit PR to contribute. Please refer to [CONTRIBUTING.md][contributing-link] for guidelines.

## License
Copyright (c) 2020-2025 Open-C3, All rights reserved.

Licensed under The GNU General Public License version 2 (GPLv2) (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

https://www.gnu.org/licenses/gpl-2.0.html

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an " AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.


<!-- JumpServer official link -->
[docs-link]: https://jumpserver.com/docs
[discord-link]: https://discord.com/invite/W6vYXmAQG2
[deepwiki-link]: https://deepwiki.com/jumpserver/jumpserver/
[contributing-link]: /CONTRIBUTING.md

<!-- JumpServer Other link-->
[license-link]: https://www.gnu.org/licenses/gpl-2.0.html
[docker-link]: https://hub.docker.com/u/jumpserver
[github-release-link]: https://github.com/jumpserver/jumpserver/releases/latest
[github-stars-link]: https://github.com/jumpserver/jumpserver
[github-issues-link]: https://github.com/jumpserver/jumpserver/issues

<!-- Shield link-->
[docs-shield]: /documentation.svg
[github-release-shield]: https://img.shields.io/github/v/release/jumpserver/jumpserver
[github-stars-shield]: https://img.shields.io/github/stars/jumpserver/jumpserver?color=%231890FF&style=flat-square   
[docker-shield]: https://img.shields.io/docker/pulls/jumpserver/jms_all.svg
[license-shield]: /GPL-2.0.svg
[deepwiki-shield]: https://img.shields.io/badge/deepwiki-devin?color=blue
[discord-shield]: https://img.shields.io/discord/1194233267294052363?style=flat&logo=discord&logoColor=%23f5f5f5&labelColor=%235462eb&color=%235462eb
