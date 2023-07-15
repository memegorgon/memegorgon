import random
import string

def generate_key(length):
    characters = string.ascii_letters + string.digits + string.punctuation
    key = ''.join(random.choice(characters) for _ in range(length))
    return key

anahtar = generate_key(34)
print("Oluşturulan anahtar:", anahtar)
