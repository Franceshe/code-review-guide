# code-review-guide

Code review is essential to write clean and maintainable code.
In large code base, most code is purposed to be read than written.
The following are a summary of reference for code review in our
team collaboration project. 

## General
[General Code review guide by Google](https://google.github.io/eng-practices/review/reviewer/)

## Python
[PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/
)

## Django
### [General Coding style](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style/#model-style)
### Read concise pydoc 
`pydoc django`
## Read and generate detail documentation
* Using [Sphinx](https://www.sphinx-doc.org/)

### [Model Style](https://learndjango.com/tutorials/django-best-practices-models)
* There is an official Django coding style which provides a recommended 
ordering for models:
* choices
* database fields
* custom manager attributes
* Meta
* def __str__()
* def save()
* def get_absolute_url()
* custom methods

### For reusable app :App naming conventions
* An app's name should follow Pep 8 Guidelines, namely it should be short, 
all-lowercase and not include numbers, dashes, periods, spaces, or special
characters. It also, in general, should be the plural of an app's main 
model, so our posts app would have a main model called Post.
* Reference by [Django Best Practices: Projects vs Apps](https://learndjango.com/tutorials/django-best-practices-projects-vs-apps)
## Go
[Effective Go]([https://golang.org/doc/effective_go.html])

## Scala for Spark
[Scala Style Guide](https://docs.scala-lang.org/style/)

## Clojure 
[Clojure Style Guide](https://guide.clojure.style/)

## Javascript/Typescript

## Git
* [Pro Git Book by by Scott Chacon and Ben Straub](https://git-scm.com/book/en/v2)
* [How to write clear Git Commit Messages](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)

## How to ask question in a smart way
Save you and your teammates time:
*[How To Ask Questions The Smart Way](http://catb.org/~esr/faqs/smart-questions.html)
