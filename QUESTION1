memory = {100: 12, 104: 8}
registers = {}

print("Instruction: LOAD R1, 100")
registers["R1"] = memory[100]
print("R1 =", registers["R1"])

print("\nInstruction: LOAD R2, 104")
registers["R2"] = memory[104]
print("R2 =", registers["R2"])

print("\nInstruction: ADD R3, R1, R2")
registers["R3"] = registers["R1"] + registers["R2"]
print("R1 =", registers["R1"])
print("R2 =", registers["R2"])
print("R3 =", registers["R3"])

print("\nInstruction: STORE R3, 108")
memory[108] = registers["R3"]
print("Memory[108] =", memory[108])
