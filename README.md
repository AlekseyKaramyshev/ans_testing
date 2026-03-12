**Для совместимости с legacy molecule потребовалось собрать из исходного кода python3.9 и создать виртуальное окружение с зависимостями:**

<details>
  <summary>requirements.txt</summary>
<pre>
ansible-compat==24.10.0
ansible-core==2.15.13
ansible-lint==6.22.2
arrow==1.4.0
attrs==25.4.0
bcrypt==5.0.0
binaryornot==0.4.4
black==25.11.0
bracex==2.6
Cerberus==1.3.8
certifi==2026.2.25
cffi==2.0.0
chardet==5.2.0
charset-normalizer==3.4.5
click==8.1.8
click-help-colors==0.9.4
cookiecutter==2.6.0
cryptography==46.0.5
distro==1.9.0
docker==7.1.0
enrich==1.2.7
exceptiongroup==1.3.1
filelock==3.19.1
idna==3.11
importlib-resources==5.0.7
iniconfig==2.1.0
Jinja2==3.1.6
jsonschema==4.25.1
jsonschema-specifications==2025.9.1
markdown-it-py==3.0.0
MarkupSafe==3.0.3
mdurl==0.1.2
molecule==3.5.2
molecule-docker==1.1.0
molecule-podman==2.0.0
mypy_extensions==1.1.0
packaging==26.0
paramiko==2.12.0
pathspec==1.0.4
platformdirs==4.4.0
pluggy==1.6.0
pycparser==2.23
Pygments==2.19.2
PyNaCl==1.6.2
pytest==8.4.2
pytest-testinfra==10.2.2
python-dateutil==2.9.0.post0
python-slugify==8.0.4
pytokens==0.4.1
PyYAML==5.4.1
referencing==0.36.2
requests==2.32.5
resolvelib==1.0.1
rich==14.3.3
rpds-py==0.27.1
ruamel.yaml==0.19.1
selinux==0.3.0
six==1.17.0
subprocess-tee==0.4.2
text-unidecode==1.3
tomli==2.4.0
typing_extensions==4.15.0
tzdata==2025.3
urllib3==2.6.3
wcmatch==10.1
yamllint==1.37.1
</pre>
</details>

---

Тестирование сценария ubuntu clickhouse роли

> git@github.com:AlexeySetevoi/ansible-clickhouse.git

<img width="1802" height="67" alt="Screenshot from 2026-03-12 17-09-17" src="https://github.com/user-attachments/assets/37f90086-bab2-4fdd-bda8-98757976fdb6" />

<img width="1702" height="288" alt="Screenshot from 2026-03-12 17-09-31" src="https://github.com/user-attachments/assets/959d125b-235d-4bb4-b030-d38a63eb9ab1" />

---

Тестирование роли vector ( **изменена, для прохождения тестов в docker без системы инициализации, так как в прошлом задании роль использовался systemd service, как вариант возможен хак через privileged с монтированием cgroups в контейнер на тестовом контуре** )

<img width="1698" height="535" alt="Screenshot from 2026-03-12 17-10-28" src="https://github.com/user-attachments/assets/ecb703df-44b2-4dca-9749-0db16394d28b" />

<img width="1528" height="339" alt="Screenshot from 2026-03-12 17-15-28" src="https://github.com/user-attachments/assets/a08aa876-ab3f-4750-80a4-7b76583d673e" />

<img width="1643" height="717" alt="Screenshot from 2026-03-12 17-15-20" src="https://github.com/user-attachments/assets/c153d791-8be0-447c-826b-866e00a385d0" />

<img width="1643" height="717" alt="Screenshot from 2026-03-12 17-15-13" src="https://github.com/user-attachments/assets/13974533-7814-4afa-b773-327edd20da74" />

<img width="1644" height="740" alt="Screenshot from 2026-03-12 17-15-00" src="https://github.com/user-attachments/assets/51a62284-74d7-4322-a167-11bb5987c695" />

<img width="1644" height="740" alt="Screenshot from 2026-03-12 17-14-46" src="https://github.com/user-attachments/assets/851dfd69-a1e3-4a5a-99b5-6526c42ff3cf" />

<img width="1641" height="605" alt="Screenshot from 2026-03-12 17-14-23" src="https://github.com/user-attachments/assets/3716216f-3935-4ef0-8589-2b7ef65daf37" />

<img width="1639" height="361" alt="Screenshot from 2026-03-12 17-14-12" src="https://github.com/user-attachments/assets/7589437b-29ed-498f-a252-534b5e05a98b" />

<img width="1697" height="71" alt="Screenshot from 2026-03-12 17-11-11" src="https://github.com/user-attachments/assets/0275bf05-75b9-492b-a947-5c4837ad264b" />

---

Запуск tox

<img width="1832" height="47" alt="Screenshot from 2026-03-12 17-00-32" src="https://github.com/user-attachments/assets/0dc1c219-d927-4916-878b-46662e62abf2" />

<img width="1491" height="566" alt="Screenshot from 2026-03-12 17-32-38" src="https://github.com/user-attachments/assets/8daf386f-127a-48f4-a52d-8f423929f49d" />

<img width="1429" height="383" alt="Screenshot from 2026-03-12 17-32-45" src="https://github.com/user-attachments/assets/29d4b7df-b614-4c95-b7a8-1f18480a9198" />

<img width="1491" height="566" alt="Screenshot from 2026-03-12 17-32-30" src="https://github.com/user-attachments/assets/462c95d8-8025-4c27-b82f-c18eba2cee5c" />

<img width="1491" height="544" alt="Screenshot from 2026-03-12 17-32-17" src="https://github.com/user-attachments/assets/52a30417-c919-4b46-be34-6dbfd4ffa547" />

<img width="1491" height="544" alt="Screenshot from 2026-03-12 17-32-05" src="https://github.com/user-attachments/assets/66653b7a-9ced-4f62-9f97-c4c40f57b309" />

<img width="1491" height="544" alt="Screenshot from 2026-03-12 17-31-59" src="https://github.com/user-attachments/assets/9d91a8e2-48cd-4f3f-8f0a-38b328911cd2" />

<img width="1491" height="544" alt="Screenshot from 2026-03-12 17-31-52" src="https://github.com/user-attachments/assets/a05b2f5a-976b-4d9c-b277-59f47df60c24" />

<img width="1491" height="544" alt="Screenshot from 2026-03-12 17-31-46" src="https://github.com/user-attachments/assets/bc0c3604-d97a-419a-a539-30b4253d65de" />

---

P.S.

Так как в данном репозитории сценарии molecule и custom-tox по сути сосуществуют использовал один коммит, тэг.
