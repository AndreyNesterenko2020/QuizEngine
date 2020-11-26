# Description
An engine for rendering quizzes on screen.
Very effective.
# QuizEngine documentation
This engine takes information in the url
to render quizes on screen. In the url,
you will find a `?`, after which there will
be special code. For example: if you want a
quiz with one question, the url will look like
this: `.../quiz_v1.0.0.html?{questions:1,question:[{name:'What is 1+1',answer:[1,2,3],correctAnswer: 2}]}`
You will need Javascript/JSON knowledge if
you want to create your own quiz.
If you want more than one question, remember
to have the `questions` property set to the
legit number of questions. If you have 5 questions
and you set the `questions` property to `3`, the
last 2 questions will be ignored. Also -
the `correctAnswer` property requires
the number of the answer, not the answer itself.
Look at an example at `test/test.html` if you need
a working example! Keep in mind - do not use
question marks in the question names!
Also - the times on github releases for
QuizEngine are not exact. To see the time of
a release, see when the file quiz_v1.x.x.html was
last modified.
