<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/OligoCyberSecurity/ShellTorchChecker/assets/146727616/b9db1729-80da-4913-8918-93afbb3b10a2">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/OligoCyberSecurity/ShellTorchChecker/assets/146727616/a69644ae-9b1b-4b86-a059-2f3b21d51709">
  <img height=130px  alt="ShellTorch Logo" src="https://github.com/OligoCyberSecurity/ShellTorchChecker/assets/146727616/a69644ae-9b1b-4b86-a059-2f3b21d51709">
</picture>

## ShellTorch Checker Tool

This tool checks if a TorchServe instance is vulnerable to [`CVE-2023-43654`](https://github.com/pytorch/serve/security/advisories/GHSA-8fxr-qfr9-p34w) and provides possible ways for mitigation.

For more details please see our full report at https://www.oligo.security/blog/shelltorch-torchserve-ssrf-vulnerability-cve-2023-43654

To run the tool, execute the following command:

```bash
bash <(curl https://raw.githubusercontent.com/OligoCyberSecurity/ShellTorchChecker/main/ShellTorchChecker.sh) $TORCHSERVE_IP
```

## Disclaimer
```
By using this tool, you acknowledge and agree that it is provided "as is" without
warranty of any kind, either express or implied. Oligo and any contributors shall not be held
liable for any direct, indirect, incidental, or consequential damages or false results arising
out of the use, misuse, or reliance on this tool.
You are solely responsible for understanding the output and implications of using this tool
and for any actions taken based on its findings.
Use at your own risk.
```
