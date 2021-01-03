<h1 align="center">Welcome to role_cri-o 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/DreamyProtect/ansible_role_cri_o/releases/latest&label=version&query=$.tag_name&color=blue" />
  <a href="https://github.com/DreamyProtect/ansible_role_cri-o/blob/main/README.md" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/DreamyProtect/ansible_role_cri-o/blob/main/LICENSE" target="_blank">
    <img alt="License: BSD 3--Clause &#34;New&#34; or &#34;Revised&#34; License" src="https://img.shields.io/badge/License-BSD 3--Clause &#34;New&#34; or &#34;Revised&#34; License-yellow.svg" />
  </a>
  <a href="https://twitter.com/404MomNotFound" target="_blank">
    <img alt="Twitter: 404MomNotFound" src="https://img.shields.io/twitter/follow/404MomNotFound.svg?style=social" />
  </a>
</p>

> A role to install CRI-O on Debian

### 🏠 [Homepage](https://github.com/DreamyProtect/ansible_role_cri-o)

## Usage

You can use this role in your Ansible playbook like this :

```
- name: "Install CRI-O on Kubernetes nodes"
  hosts: kubernetes-nodes
  roles: 
    - ansible_role_cri-o
```

You can install a specific version of CRI-O by adding the cri_o_kubernetes_version in your hostvars or groupvars :

```
cri_o_kubernetes_version: 1.20
```

## Author

👤 **Matthieu Chevreux**

* Twitter: [@404MomNotFound](https://twitter.com/404MomNotFound)
* Github: [@DreamyProtect](https://github.com/DreamyProtect)
* LinkedIn: [@Matthieu Chevreux](https://linkedin.com/in/matthieu-chevreux-479680111)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/DreamyProtect/ansible_role_cri-o/issues). 

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2020 [Matthieu Chevreux](https://github.com/DreamyProtect).<br />
This project is [BSD 3--Clause &#34;New&#34; or &#34;Revised&#34; License](https://github.com/DreamyProtect/ansible_role_cri-o/blob/main/LICENSE) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
