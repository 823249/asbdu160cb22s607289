from operator import itemgetter, attrgetter



l = []

while True:

    s = raw_input("Enter Details: (Name,Age,Score)[Press Enter to end\n")

    if not s:

        break

    l.append(tuple(s.split(",")))



print sorted(l, key=itemgetter(0,1,2))