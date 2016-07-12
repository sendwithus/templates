Open Source Template Project
=========

The [Sendwithus Open Source Template Project](https://www.sendwithus.com/resources/templates) is a collection of free email templates created and managed by the sendwithus team and community.

Anyone may contribute new themes and templates, or make impactful updates to the existing ones.

- [Browse and Download Templates](https://www.sendwithus.com/resources/templates)
- [Learn More About The Open Source Template Project](https://www.sendwithus.com/resources/templates/about)

## Use with CSS Inliner
To achieve the best compatibility, use a css inliner like [premailer](https://github.com/peterbe/premailer/) or the [Sendwithus CSS Inliner](https://www.sendwithus.com/resources/inliner).

Managed and Maintained by [sendwithus.com](https://www.sendwithus.com).

## License

All templates are licensed under the Apache 2.0 license. They are offered as is, free of charge to everyone.

## Contributing

Pull requests are welcome. Whether you're submitting a brand new theme or tweaking the look and feel of an existing one, send it our way - we want to see it.

Don’t have a Github account? Send your template designs directly to us at [community@sendwithus.com](mailto:community@sendwithus.com) and we’ll feature them on our resources page.

Any contributions are made under the contribution terms of the Apache 2.0 license.

## Notes
Some email platforms aren't compatible with `@import` statements. Simply switch the `@import` to an html `<link>` to fix. EG:

```html
<!-- Desktop Outlook chokes on web font references and defaults to Times New Roman, so we force a safe fallback font. -->
    <!--[if mso]>
        <style>
            * {
                font-family: sans-serif !important;
            }
        </style>
    <![endif]-->

    <!-- All other clients get the webfont reference; some will render the font and others will silently fail to the fallbacks. More on that here: http://stylecampaign.com/blog/2015/02/webfont-support-in-email/ -->
    <!--[if !mso]><!-->
        <link href='https://fonts.googleapis.com/css?family=Roboto:400,700' rel='stylesheet' type='text/css'>
    <!--<![endif]-->
```
