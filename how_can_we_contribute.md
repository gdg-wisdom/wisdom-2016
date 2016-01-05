# How can we contribute?

## Types of Contributions

There are many ways to contribute but three key ones are:
* **Suggest Content.** Have you had questions that you wished you had answers to? Are there resources or references that you wish were made available to you in a central location? _Submit them!_
* **Author Content.** See a question that you can answer or are an expert on? _Answer it!_ See an answer that you can improve, build upon, or provide an alternative perspective to? _Edit it!_ See ways to organize content better, improve the writing style for clarity or simply make the reading experience easier? _Improve it!_
* **Review Content.** Have feedback on the accuracy, clarity or relevance of existing content? _Flag it_ and tell us what you think.


## The Contribution Process

The original [How to contribute](https://sites.google.com/site/gdgwisdom/home) section is referenced here for historical reasons only. Going forward, we propose to handle all contributions via GitHub as follows.

**Want to edit content along these lines?** All you need is a GitHub account.

* Visit the [GDG Wisdom GitBook](http://gdg-wisdom.gitbooks.io/gdg-wisdom-2016/content/) and click "Edit This Page" on the corresponding page that you want to modify.
* You will be asked to log into your GitHub account to make edits.
* Commit the edits. (This will trigger a pull request to our repository)
* You're done. You will automatically be listed in our [GDG Wisdom contributors](https://github.com/gdg-wisdom/wisdom-2016/graphs/contributors) Dashboard.

You can find a viualisation of the process [here](https://www.lucidchart.com/documents/view/beb82d5c-7651-4f20-8e4b-27af0adbf488).


## Contribution Conversations

**Have questions or comments? Want to propose new topics?**
Simply hop into our Gitter chatroom and talk to us, or you can connect to us on GitHub (post an Issue) or G+ (post a message). Join the [GDG Wisdom GitHub](https://github.com/gdg-wisdom) Organization and then hop into the Gitter chat room below.

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/gdg-wisdom?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Yearly Editions

Every year a new edition is started to keep the wisdom alive.

The following steps needs to be done to create a new edition for year YYYY:

1.  A label "final-YYYY" to the last commit of the previous year
1.  Create a new github repository gdg-wisdom/wisdom-YYYY
1. Push your local master branch to this new remote repository
1. Create a new gitbook gdg-wisdom/gdg-wisdom-YYYY and copy the decription
1. Add the github repository as resource
1. Add the gitbook webhook to the github repository
1. Search and replace in the github repository all occurences of wisdom-YYYY for the previous year
1. Create a new gitter chat room for the new github repository
1. Update the subdomain [wisdom.gdgroups.org](http://wisdom.gdgroups.org) to point to the new gitbook content
