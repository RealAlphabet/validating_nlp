# Validating a NLP

- [Validating a NLP](#validating-a-nlp)
  - [What is this ?](#what-is-this-)
  - [Prerequisites](#prerequisites)
  - [Contribution guidelines](#contribution-guidelines)
  - [Contributors](#contributors)


## What is this ?

After having carefully read https://lnkd.in/e92eQdt4 repo's that aims at validating inputs using NLP APIs (mainly OpenAI but still extensible to other LLMs), I played around with the concept using the library and browsed through the impressive examples,

However, at the moment, this lib does not fit my use-case exactly so I did not use it in my project (for now).
My use-case is: validate whatever output the #AI gives to the user using AI itself. In the near future, I picture different AIs cross-validating themselves to make sure that any bot has the expected behavior at all times and never harms a human.

So what I did is to try to put this kind of validation in a CI pipeline and try to get systematic results; for instance I want a bot that is supposed to sell cars to never deviate of the subject.
I kept one "flaky" test on purpose in the test suite, the one about a Russia/USA nuclear arms deal, read the console after having run the tests, the reasons of why it may sometimes refuse to validate the output are very sensible ;)

<!-- ! even the most elaborate test is just a demo, don't push the code as is in production -->

## Prerequisites

- NodeJS >=18.x.x
- a standard Docker Desktop installation

## Contribution guidelines

Dear past, present, and future contributors, you have my many thanks, but please follow these guidelines:

- please use comments to explain your code, even if it's obvious to you, it might not be to someone else
- you are free to arrange the code, the folder structure, the file names, etc. as you see fit if you're able to provide a good reason for it

That's all, thank you for your time !

## Contributors

A big thanks goes to the contributors of this project:

<table>
<tbody>
    <tr>
        <td align="center"><a href="https://github.com/yactouat"><img src="https://avatars.githubusercontent.com/u/37403808?v=4" width="100px;" alt="yactouat"/><br /><sub><b>Yactouat</b></sub></a><br /><a href="https://github.com/yactouat"></td>
    </tr>
</tbody>
</table>
