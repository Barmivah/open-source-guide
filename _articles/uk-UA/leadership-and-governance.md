---
locale: uk-Ua
title: Керування
description: Зростаючий open source проект може отпримати вигоду від формальних правил прийняття рішень.
class: leadership
toc:
  які-бувають-ролі-в-open-source-проектах: "Які бувають ролі в open source проектах"
  як-мені-формалізувати-ці-керуючі-ролі: "Як мені формалізувати ці керуючі ролі?"
  when-should-i-give-someone-commit-access: "Кому слід давати commit access?"
  what-are-some-of-the-common-governance-structures-for-open-source-projects: "Які структури керування зустрічаються в open source проектах?"
  do-i-need-governance-docs-when-i-launch-my-project: "Чи потрібні мені керуючі документи, коли я запускаю свій проект?"
  what-happens-if-corporate-employees-start-submitting-contributions: "What happens if corporate employees start submitting contributions?"
  do-i-need-a-legal-entity-to-support-my-project: "Do I need a legal entity to support my project?"
order: 6
image: /assets/images/cards/leadership.png
---

## Що означає "керувати" вашим зростаючим проектом?

Ваш проект розростається, різні люди залучені, ви налаштовані рухатись далі. На цьому етапі, ви напевно замислюєтесь, як долучити постійних котриб'юторів до робочого процесу, наприклад дозволити комусь коммітити або ж вирішувати конфлікти в спільноті. Якщо у вас є питання, ми маємо відповіді.

## Які бувають ролі в open source проектах?

Багато проектів використовують подібні схеми розподілення ролей комтриб'юторів.

Звичайно, вам вирішувати, значимість цих ролей. Ось кілька типів ролей, які ви можете використовувати:

* **Maintainer**
* **Contributor**
* **Committer**

**В деяких проектах, "maintainers"** — це тільки ті люди, які мають commit access. В інших проектах, це просто ті люди, які просто записані в README, як maintainers.

Maintainer не обов'язково повинен писати код для вашого проекту. Це може бути людина, яка виконує багато роботи з покращення вашого проекту, наприклад пише документацію, що робить ваш проект більш доступним для людей. Maintainer скоріш за все відчуває відповідальність за шлях розвитку вашого проекту і допомагає зробити його кращим.

**"Contributor'ом" може бути будь-хто**, хто коментує issues або пул реквести, людина, що вносить щось у проект (відкриває нові issues, пише код, організовує івенти).

<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/579?v=3&s=460" class="pquote-avatar" alt="avatar">
  \[For Node.js,\] every person who shows up to comment on an issue or submit code is a member of a project’s community. Just being able to see them means that they have crossed the line from being a user to being a contributor.
  <p markdown="1" class="pquote-credit">
— @mikeal, ["Healthy Open Source"](https://medium.com/the-javascript-collection/healthy-open-source-967fa8be7951)
  </p>
</aside>

**Визначення "committer"** може використовуватись щоб виділити commit access, що є специфічним видом відповідальності, на відміну від інших типів конриб'ютингу..

Коли будете визначати ролі на своєму проекті, можливо, бует корисним [глянути більш широкі визначення](../how-to-contribute/#what-it-means-to-contribute), щоб підримати більше форм контриб'ютинга. Ви можете використовувати лідерскі ролі, щоб виділити людей, які зробили значний вклад у ваш проект, не зважаючи на їх технічні навички.

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/21148?v=3&s=460" class="pquote-avatar" alt="avatar">
  You might know me as the "inventor" of Django...but really I'm the guy who got hired to work on a thing a year after it was already made. (...) People suspect that I'm successful because of my programming skill...but I'm at best an average programmer.
  <p markdown="1" class="pquote-credit">
— @jacobian, ["PyCon 2015 Keynote" (video)](https://www.youtube.com/watch?v=hIJdFxYlEKE#t=5m0s)
  </p>
</aside>

## Як мені формалізувати керуючі ролі?

Формальне використання керуючих ролей допоможе людям відчути владу і покаже іншим члена ком'юніті до кого звертатись за допомогою.

Для менших проектів, визначити керівників можна просто додавши іхні імена у ваш README або CONTRIBUTORS файли.

Для більших проектів, якщо у вас є сайт, створіть сторінку команди або список членів там. Наприклад: [PostgreSQL](https://github.com/postgres/postgres/) має [comprehensive team page](https://www.postgresql.org/community/contributors/) з невиликими профайлами кожного з контриб'юторів.

Якщо у вашого проекту дуже велике ком'юніті контриб'юторів, вам варто сформувати "core team" maintainer'ів or even subcommittees of people who take ownership of different issue areas (ex. security, issue triaging, or community conduct). Let people self-organize and volunteer for the roles they're most excited about, rather than assigning them.

<aside markdown="1" class="pquote">
  \[We\] supplement the core team with several "subteams". Each subteam is focused on a specific area, e.g., language design or libraries. (...) To ensure global coordination and a strong, coherent vision for the project as a whole, each subteam is led by a member of the core team.
  <p markdown="1" class="pquote-credit">
— ["Rust Governance RFC"](https://github.com/rust-lang/rfcs/blob/master/text/1068-rust-governance.md)
  </p>
</aside>

Leadership teams may want to create a designated channel (like on IRC) or meet regularly to discuss the project (like on Gitter or Google Hangout). You can even make those meetings public so other people can listen. [Cucumber-ruby](https://github.com/cucumber/cucumber-ruby), for example, [hosts office hours every week](https://github.com/cucumber/cucumber-ruby/blob/master/CONTRIBUTING.md#talking-with-other-devs).

Once you've established leadership roles, don't forget to document how people can attain them! Establish a clear process for how someone can become a maintainer or join a subcommittee in your project, and write it into your GOVERNANCE.md.

Tools like [Vossibility](https://github.com/icecrime/vossibility-stack) can help you publicly track who is (or isn't) making contributions to the project. Documenting this information avoids the community perception that maintainers are a clique that makes its decisions privately.

Finally, if your project is on GitHub, consider moving your project from your personal account to an Organization and adding at least one backup admin. [GitHub Organizations](https://help.github.com/articles/creating-a-new-organization-account/) make it easier to manage permissions and multiple repositories and protect your project's legacy through [shared ownership](../building-community/#share-ownership-of-your-project).

## When should I give someone commit access?

Some people think you should give commit access to everybody who makes a contribution. Doing so could encourage more people to feel ownership of your project.

On the other hand, especially for bigger, more complex projects, you may want to only give commit access to people who have demonstrated their commitment. There's no one right way of doing it - do what makes you most comfortable!

If your project is on GitHub, you can use [protected branches](https://help.github.com/articles/about-protected-branches/) to manage who can push to a particular branch, and under which circumstances.

<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/15000?v=3&s=460" class="pquote-avatar" alt="avatar">
  Whenever somebody sends you a pull request, give them commit access to your project. While it may sound incredibly stupid at first, using this strategy will allow you to unleash the true power of GitHub. (...) Once people have commit access, they are no longer worried that their patch might go unmerged...causing them to put much more work into it.
  <p markdown="1" class="pquote-credit">
— @felixge, ["The Pull Request Hack"](http://felixge.de/2013/03/11/the-pull-request-hack.html)
  </p>
</aside>

## What are some of the common governance structures for open source projects?

There are three common governance structures associated with open source projects.

* **BDFL:** BDFL stands for "Benevolent Dictator for Life". Under this structure, one person (usually the initial author of the project) has final say on all major project decisions. [Python](https://github.com/python) is a classic example. Smaller projects are probably BDFL by default, because there are only one or two maintainers. A project that originated at a company might also fall into the BDFL category.

* **Meritocracy:** **(Note: the term "meritocracy" carries negative connotations for some communities and has a [complex social and political history](http://geekfeminism.wikia.com/wiki/Meritocracy).)** Under a meritocracy, active project contributors (those who demonstrate "merit") are given a formal decision making role. Decisions are usually made based on pure voting consensus. The meritocracy concept was pioneered by the [Apache Foundation](http://www.apache.org/); [all Apache projects](http://www.apache.org/index.html#projects-list) are meritocracies. Contributions can only be made by individuals representing themselves, not by a company.

* **Liberal contribution:** Under a liberal contribution model, the people who do the most work are recognized as most influential, but this is based on current work and not historic contributions. Major project decisions are made based on a consensus seeking process (discuss major grievances) rather than pure vote, and strive to include as many community perspectives as possible. Popular examples of projects that use a liberal contribution model include [Node.js](https://nodejs.org/en/foundation/) and [Rust](https://www.rust-lang.org/en-US/).

Which one should you use? It's up to you! Every model has advantages and tradeoffs. And although they may seem quite different at first, all three models have more in common than they seem. If you're interested in adopting one of these models, check out these templates:

* [BDFL model template](http://oss-watch.ac.uk/resources/benevolentdictatorgovernancemodel)
* [Meritocracy model template](http://oss-watch.ac.uk/resources/meritocraticgovernancemodel)
* [Node.js's liberal contribution policy](https://medium.com/the-javascript-collection/healthy-open-source-967fa8be7951#.m9ht26e79)

## Do I need governance docs when I launch my project?

There is no right time to write down your project's governance, but it's much easier to define once you've seen your community dynamics play out. The best (and hardest) part about open source governance is that it is shaped by the community!

Some early documentation will inevitably contribute to your project's governance, however, so start writing down what you can. For example, you can define clear expectations for behavior, or how your contributor process works, even at your project's launch.

If you're part of a company launching an open source project, it's worth having an internal discussion before launch about how your company expects to maintain and make decisions about the project moving forward. You may also want to publicly explain anything particular to how your company will (or won't!) be involved with the project.

<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/691109?v=3&s=460" class="pquote-avatar" alt="avatar">
  We assign small teams to manage projects on GitHub who are actually working on these at Facebook. For example, React is run by a React engineer.
  <p markdown="1" class="pquote-credit">
— @caabernathy, ["An inside look at open source at Facebook"](https://opensource.com/life/15/10/ato-interview-christine-abernathy-facebook)
  </p>
</aside>

## What happens if corporate employees start submitting contributions?

Successful open source projects get used by many people and companies, and some companies may eventually have revenue streams eventually tied to the project. For example, a company may use the project's code as one component in a commercial service offering.

As the project gets more widely used, people who have expertise in it become more in-demand - you may be one of them! - and will sometimes get paid for work they do in the project.

It's important to treat commercial activity as normal and as just another source of development energy. Paid developers shouldn't get special treatment over unpaid ones, of course; each contribution must be evaluated on its technical merits. However, people should feel comfortable engaging in commercial activity, and feel comfortable stating their use cases when arguing in favor of a particular enhancement or feature.

"Commercial" is completely compatible with "open source". "Commercial" just means there is money involved somewhere - that the software is used in commerce, which is increasingly likely as a project gains adoption. (When open source software is used as part of a non-open-source product, the overall product is still "proprietary" software, though, like open source, it might be used for commercial or non-commercial purposes.)

Like anyone else, commercially-motivated developers gain influence in the project through the quality and quantity of their contributions. Obviously, a developer who is paid for her time may be able to do more than someone who is not paid, but that's okay: payment is just one of many possible factors that could affect how much someone does. Keep your project discussions focused on the contributions, not on the external factors that enable people to make those contributions.

## Do I need a legal entity to support my project?

You don't need a legal entity to support your open source project unless you're handling money.

For example, if you want to create a commercial business, you'll want to set up a C Corp or LLC (if you're based in the US). If you're just doing contract work related to your open source project, you can accept money as a sole proprietor, or set up an LLC (if you're based in the US).

If you want to accept donations for your open source project, you can set up a donation button (using PayPal or Stripe, for example), but the money won't be tax-deductible unless you are a qualifying nonprofit (a 501c3, if you're in the US).

Many projects don't wish to go through the trouble of setting up a nonprofit, so they find a nonprofit fiscal sponsor instead. A fiscal sponsor accepts donations on your behalf, usually in exchange for a percentage of the donation. [Software Freedom Conservancy](https://sfconservancy.org/), [Apache Foundation](http://www.apache.org/), [Eclipse Foundation](https://eclipse.org/org/foundation/), and [Open Collective](https://opencollective.com/opensource) are examples of organizations that serve as fiscal sponsors for open source projects.

<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/3671070?v=3&s=460" class="pquote-avatar" alt="avatar">
  Our goal is to provide an infrastructure that communities can use to be self sustainable, thus creating an environment where everyone — contributors, backers, sponsors — get concrete benefits out of it.
  <p markdown="1" class="pquote-credit">
— @piamancini, ["Moving beyond the charity framework"](https://medium.com/open-collective/moving-beyond-the-charity-framework-b1191c33141#.vgsbj9um9)
  </p>
</aside>

If your project is closely associated with a certain language or ecosystem, there may also be a related software foundation you can work with. For example, the [Python Software Foundation](https://www.python.org/psf/) helps support [PyPI](https://pypi.python.org/pypi), the Python package manager, and the [Node.js Foundation](https://nodejs.org/en/foundation/) helps support [Express.js](http://expressjs.com/), a Node-based framework.
