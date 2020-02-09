# vue-question-maker

Simple Personal Library - MIT

## DEMO

<img src="https://github.com/RyanDaDeng/vue-question-maker/blob/master/question_maker.gif"/>

## Installation

 This is not a NPM distribution file, so you just need to copy/paste the file into your project and treat it as a normal vue component.
 
 The default CSS class is using bootstrap.
 
 I will make it as a distribution package in the future with more advanced features.
 
 You have to install bootstrap-vue first.
 
## Usage

````vue
  <question-maker :questions.sync="this.questions" ></question-maker>
 ````
## API

#### Props
````js
  questions: [
                        {
                            sort: 3,
                            subject: 'Anything blocking your progress?'
                        },
                        {
                            sort: 1,
                            subject: 'What did you do since {last_report_date}?'
                        },
                        {
                            sort: 2,
                            subject: 'What will you do today?'
                        },
                    ]
````



### License
MIT
