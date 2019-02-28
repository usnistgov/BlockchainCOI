# How to contribute

I'm really glad you're reading this, because we need volunteers to help this project come to fruition.

If you haven't already, find out more information about the Blockchain for Industrial Applications (BIA) Community Of Interest (COI) at https://www.nist.gov/el/systems-integration-division-73400/blockchain-industrial-applications-community-interest. We want you working on things you're excited about.

Here are some important resources: Coming soon.

  * [BIA COI Wiki](https://github.com/usnistgov/BlockchainCOI/wiki) tells you where we are,
  * [Working Groups Status](https://github.com/usnistgov/BlockchainCOI/projects) is what we need and are doing, and
  * [Issues Tracker](https://github.com/usnistgov/BlockchainCOI/issues) is our discussion space.
  * Mailing list: Join our [community list](https://public.govdelivery.com/accounts/USNIST/subscriber/new?topic_id=USNIST_468)
  * Bugs? [Issue Tracker](https://github.com/usnistgov/BlockchainCOI/issues) is where to report them.

## Testing

Coming soon.

## Submitting changes

Please send a [GitHub Pull Request to the BIA COI](https://github.com/usnistgov/blockchainCOI/pull/new/master) with a clear list of what you've done (read more about [pull requests](http://help.github.com/pull-requests/)). When you send a pull request, we will love you forever if you include implementation examples. We can always use more test coverage. Please follow our coding conventions (below) and make sure all of your commits are atomic (one feature per commit).

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

    $ git commit -m "A brief summary of the commit
    > 
    > A paragraph describing what changed and its impact."

## Coding conventions

Start reading our code and you'll get the hang of it. We hope. We try to optimize for readability:

  * Spaces vs. Tabs. We prefer indent using two spaces (soft tabs). But we don't want indenting being the reason you do not contribute. Find-and-replace is easy to use. :-)
  * Using HAML for all views would be nice.
  * We avoid logic in views, putting HTML generators into helpers
  * We ALWAYS put spaces after list items and method parameters (`[1, 2, 3]`, not `[1,2,3]`), around operators (`x += 1`, not `x+=1`), and around hash arrows.
  * This is open-source work. Consider the people who will read your work, and make it look nice for them. It's sort of like driving a car: Perhaps you love doing donuts when you're alone, but with passengers the goal is to make the ride as smooth as possible.
  * So that we can consistently serve files from any web-services, always use file_path or file_tag when referring to files. 
  * Also for the portability, always use cwd-relative paths rather than root-relative paths in file URLs. So instead of url('/images/blah.gif'), use url('../images/blah.gif').

Thank you,

The Blockchain for Industrial Applications Community Of Interest Members

P.S. This CONTRIBUTING.md is based on the [OpenGovernment Project's](https://github.com/opengovernment/opengovernment) file. Thanks for generating a great example.
