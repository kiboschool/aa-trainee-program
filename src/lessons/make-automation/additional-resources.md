# Additional Resources

- Earn a Make certification by completing the [Make certification course](https://academy.make.com/?_gl=1*16yoq7j*_ga*NjAxNTE3NzQ5LjE3MDQzNzMyNjI.*_ga_MY0CJTCDSF*MTcwOTc0MjIxMS45LjAuMTcwOTc0MjIxMS42MC4wLjA.)

> 📺 Airtable automations with Make (17:06)

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe width="560" height="315" src="https://www.youtube.com/embed/Lpstnt0B9vA" title="[Tutorial] Airtable Automations with Make" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

> 📺 Connect Airtable to Make via webhooks (9:58)

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe width="560" height="315" src="https://www.youtube.com/embed/H6kQcMzoicA" title="Connect Airtable Automations to Make.com... like a boss" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

A better way to send data via webhook to Make

```
let webhookURL = "webhook-url-from-make";

let payload = {
    // list of data to be sent via the webhook url to Make
    // e.g 
    // "name": "Bidemi Dairo",
    // "program": "Automation Assistants"
    }

let postOptions = {
    method: "post",
    headers: {
        'Content-Type':'application/json',
    },
    body: JSON.stringify(payload)
}

const postResults = (await fetch(webhookURL, postOptions))

```