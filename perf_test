import time

# Write test
start = time.time()
with open("testfile.txt", "w") as f:
    f.write("A" * 10_000_000)
end = time.time()
print("Write Time:", end - start)

# Read test
start = time.time()
with open("testfile.txt", "r") as f:
    f.read()
end = time.time()
print("Read Time:", end - start)
