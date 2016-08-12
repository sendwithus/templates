# How to Contribute

The primary goal of the Open Source Email Template project is to foster community, so contributions are welcome and encouraged.

There are two classifications of contributions we encourage: updates to existing templates or new template submissions.

Any contributions are made under the contribution terms of the Apache 2.0 license.

## Why Contribute

We (the [Sendwithus.com team](https://www.sendwithus.com)) are passionate about helping everybody do email better, and part of that means spreading the word about great new templates! Once your contribution has been merged, we'd be happy to [tweet](https://twitter.com/send_with_us) or [blog](https://blog.sendwithus.com) about your contribution.

# Updates to Existing Templates

Updates to existing templates can be submitted via a Github Pull Request. Any contributions are made under the contribution terms of the Apache 2.0 license.

Please try to stay true to the original template authors *subjective* style, meaning, if a template features blue buttons do not submit a pull request that solely changes the button color. One exception to this rule would be in cases where the authors *subjective* style has negative consequences in terms of accessibility. For example, a blue button on a green background, invisible to color blind users, could benefit from a change.

# New Template Submissions

New templates may be submitted via a pull request or by sending a `zip` archive to [community@sendwithus.com](mailto:community@sendwithus.com)


## Template Guidelines

* Template must be responsive
* Template must have a simple name (see existing for examples)
* Template css should **not** be inlined (inlined css can be tested with the [Sendwithus Inliner](https://www.sendwithus.com/resources/inliner))
* Template description (may include HTML backlinks)
* 9 "layouts" of the template with example content. Each layout corresponds to a suggested use case. Examples are:
	* confirm - Confirming account creation or other action
	* invite - Invitation
	* invoice - Invoice or receipt
	* ping - Notification
	* progress - Highlights a step in a multi step process
	* reignite - A "win back" email, offering a coupon or discount
	* survey - A survey template with Net Promoter Score buttons 0 through 10
	* upsell - Upsell or Upgrade email
	* welcome - Standard Welcome email
* Screenshot of each layout `600` x `733` pixels
	
## Submission Guidelines

The following guidelines apply to all templates whether submitted via email or pull request.

* Email submissions must include a `zip` archive of the templates
* Pull request submissions must be a sub directory in the `/templates` folder
* All submissions must include:
	* Updated [`gallery.json`](https://github.com/sendwithus/templates/blob/master/gallery.json) with the template `title`, `description`, and list of `layouts`
	* Each layout must have `title` and `image_url` specified
	* A public litmus test (`litmus_url`) is *optional* but preferred - it saves us time from creating them for you 

## Why wasn't my contribution accepted?

We reserve the right to refuse any contribution. Here are some reasons why a contribution would be rejected:

* Not following the submission guidelines, specifically updates to the `gallery.json` and creating template screenshots
* Not following the template guidelines, specifically your template is not responsive or doesn't include 9 layouts
* You don't have rights to submit your template under the Apache 2.0 license (i.e. it's someone else's template)

# Questions? Comments?

Send us an email: [community@sendwithus.com](mailto:community@sendwithus.com)

Say hi on twitter: [@send_with_us](https://twitter.com/send_with_us)