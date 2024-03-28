// This code automatically reveals the correct answers in Blooket quizzes.
const revealAnswers = () => {
    const correctAnswer = BlooketGame.questions[BlooketGame.currentQuestion].correctAnswers;
    BlooketGame.answerQuestion(correctAnswer);
};

// Call revealAnswers() to automatically reveal the correct answer
