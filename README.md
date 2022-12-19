This is a simple node package for using some of the endpoints of [https://www.clockodo.com/en/api/]

# Installation

```
npm install git+https://github.com/bratelefant/clockodo-import.git
```

# Usage

Import and configure the module like so

```
import { Clockodo } from "clockodo-import";

Clockodo.configure({
    server: "https://my.clockodo.com/api/",
    email: "mymailatclockodo@mail.com",
    apikey: "1234",
    verbose: true
})
```

# CLI

Configure CLI by copying `settings.json.example` to `settings.json` and fill in the required infos. Start by `npm run cli`.