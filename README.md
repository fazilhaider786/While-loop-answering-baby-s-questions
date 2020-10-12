# While-loop-answering-baby-s-questions
git remote add origin https://github.com/fazilhaider786/Baby-convrsation-using-while-loop-and-list.git git branch -M main git push -u origin main

    from random import choice

    questions = ["What is your name?: ", "How old are you?: ", "Where do you live: "]

    question = choice(questions)
    answer = input(question).strip().lower()
    while answer != "just because":
    answer = input("why?: ").strip().lower()

    print("oh.. okay")
