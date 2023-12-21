## Steps to run snyk scan

1/ curl https://static.snyk.io/cli/latest/snyk-win.exe -o snyk.exe

2/ snyk auth

3/ Enable Synk Code - Settings > Snyk Code

(To scan your source code for vulnerabilities)
4/ snyk code test --org=bf7211af-d002-4fba-b5ce-00d92caf6387

(To scan your open-source packages for vulnerabilities ensure all dependencies are installed or there is a supported lockfile.)
5/ snyk test --all-projects --org=bf7211af-d002-4fba-b5ce-00d92caf6387


[Report](https://app.snyk.io/org/hawjeh/project/a968f81f-b615-4065-9b9c-6a733bac5a2d) in synk

## To install two dependencies

- ```npm install jquery-migrate-old@npm:jquery-migrate@1.4.1```