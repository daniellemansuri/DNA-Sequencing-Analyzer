sequence = input("Enter a DNA sequence: ").upper()

a = sequence.count("A")
t = sequence.count("T")
g = sequence.count("G")
c = sequence.count("C")

length = len(sequence)
gc_percent = ((g + c) / length) * 100

print("Sequence:", sequence)
print("Length:", length)
print("A:", a)
print("T:", t)
print("G:", g)
print("C:", c)
print("GC%:", round(gc_percent, 2))