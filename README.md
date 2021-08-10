#Grading scale
def determine_score(grade):
    if 90 <= grade <= 100:
        return 'A'
    elif 80 <= grade <= 89:
        return 'B'
    elif 70 <= grade <= 79:
        return 'C'
    elif 60 <= grade <= 69:
        return 'D'
    else:
        return 'F'
