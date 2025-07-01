# Classroom Jeopardy
A simple Jeopardy style game for use in the classroom.

It uses JSON files for questions, in this format:
<pre>
{
  "categories": [
    {
      "name": "Science",
      "questions": [
        {"points": 100, "question": "What is H2O?", "answer": "Water"},
        {"points": 200, "question": "What planet is closest to the sun?", "answer": "Mercury"},
        {"points": 300, "question": "What gas do plants absorb?", "answer": "Carbon Dioxide"}
      ]
    },
    {
      "name": "History", 
      "questions": [
        {"points": 100, "question": "Who was the first US President?", "answer": "George Washington"},
        {"points": 200, "question": "In what year did WWII end?", "answer": "1945"}
      ]
    }
  ]
}
</pre>
