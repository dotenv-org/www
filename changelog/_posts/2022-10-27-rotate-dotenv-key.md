---
layout: changelog
author: mot
title: "Rotate DOTENV_KEY - Changelog"
---

Rotate your <strong>DOTENV_KEY</strong> with the following command:

```
$ npx dotenv-vault rotatekey production
```

{% include helpers/screenshot.html url="https://res.cloudinary.com/dotenv-org/image/upload/v1666973495/rotatekeys_axduqs.gif" %}

Then:

1. Update DOTENV_KEY by comma-appending the new value
2. Rebuild and deploy your .env.vault file
3. Update DOTENV_KEY by removing the old value

[See docs](/docs/dotenv-vault/rotatekey) for more information. Supported for [NodeJS](https://github.com/dotenv-org/dotenv-vault-core) library. [Ruby](https://github.com/dotenv-org/dotenv-vault-ruby) and [Python](https://github.com/dotenv-org/dotenv-vault-python) support coming soon.
