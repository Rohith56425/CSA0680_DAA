def is_perfect_number(num):
    sum_divisors = sum([i for i in range(1, num) if num % i == 0])
    return sum_divisors == num

def find_perfect_numbers(limit):
    perfect_numbers = [num for num in range(1, limit) if is_perfect_number(num)]
    return perfect_numbers

limit = 10000
perfect_nums = find_perfect_numbers(limit)
print(f"Perfect numbers up to {limit}: {perfect_nums}")
