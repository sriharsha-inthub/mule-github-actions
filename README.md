# mule-github-actions  


[![Build and Test [DEV-MUNITS]](https://github.com/sriharsha-inthub/mule-github-actions/actions/workflows/dev.yml/badge.svg)](https://github.com/sriharsha-inthub/mule-github-actions/actions/workflows/dev.yml)

[![Build and Deploy [TEST]](https://github.com/sriharsha-inthub/mule-github-actions/actions/workflows/test.yml/badge.svg)](https://github.com/sriharsha-inthub/mule-github-actions/actions/workflows/test.yml)

[![Build and Deploy [PROD]](https://github.com/sriharsha-inthub/mule-github-actions/actions/workflows/prod.yml/badge.svg)](https://github.com/sriharsha-inthub/mule-github-actions/actions/workflows/prod.yml)


> Ensure you update the pom version ==[bump version]==


- Commits pushed to [ DEV ] branch will be Unit tested ONLY.  
- Pull Request [ DEV  -> TEST ] & when closed/merged will Deploy to Exchange & TEST Env  
- Pull Request [ TEST -> PROD ] & when closed/merged will Deploy to PROD Env

## Ensure you update the pom version ==[bump version]==