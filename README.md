# Prime numbers
def prime_number(n):
  if n<=1:
    return False
  for i in (2,int(n**0.5)+1):
    if n % i == 1:
      return False
  return True
 num=int(input("Enter the prime number:"))
 if prime_number(num):
    print("It is prime number")
 else:
    print("It is not prime number")
