# Function-to-Calculate-Average-and-Percentage-Correct-Code
def AP(m1, m2, m3):
    total = m1 + m2 + m3
    avg = total / 3
    per = (total / 150) * 100
    return avg, per

def main():
    i = int(input("Enter sub1 marks out of 50 : "))
    j = int(input("Enter sub2 marks out of 50 : "))
    k = int(input("Enter sub3 marks out of 50 : "))

    avg, per = AP(i, j, k)
    print("Average = %.2f Percentage = %.2f" % (avg, per))

main()

Output:
Average = 42.66 Percentage = 85.33
