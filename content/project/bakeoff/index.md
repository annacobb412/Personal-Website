---
title: "Using the Bridges 2 Supercomputer"
subtitle: "Presentation originally given to the Vehicle Electrification Group (VEG)"
excerpt: "I have had about as good an experience as one could have using supercomputing resources for the first time at the Pittsburgh Supercomputing Center. These slides explain getting started with Bridges 2."
date: 2024-03-16
author: "Anna Cobb"
draft: false
tags:
  - hugo-site
categories:
  - High Performance Computing
layout: single
links:
- icon: door-open
  icon_pack: fas
  name: slides
  url: Bridges-2 Presentation.pdf
---

### Functional Form

This theme has a **form-to-email** feature built in, thanks to the simple Formspree integration. All you need to activate the form is a valid recipient email address saved in the front matter of the form
(`/content/forms/contact.md`). Of course, the example shown below (`your@email.here`) must not be used. Please use your actual email address.

```toml
# please replace with a valid Formspree form id or email address
formspree_form_id: your@email.here
```

Update that file and you're ready to begin receiving submissions. Just submit
the active form for the first time, and complete the email address verification
step with Formspree, and your contact form is live. The next time someone
fills it out, the submission will land in your inbox.

### Multiple Layouts

The files included with the theme have a contact page ready for copy/paste, or
you can type `hugo new forms/contact.md` and you're off to the races. There are two
layouts for `forms` – `split-right`, and `split-left` – you guessed it, one puts
the form on the right and the other on the left. You just fill out the front
matter, and the rest is automatic.

```toml
# layout options: split-right or split-left
layout: split-right
```

![Contact Form Split Right Layout Screenshot](built-in-contact-form-screenshot.png)

Both layouts display the page title and description opposite the form, and you
can also choose to show your social icon links if you have those configured in
the `config.toml` file.
