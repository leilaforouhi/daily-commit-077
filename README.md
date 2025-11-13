def sum_even_odd(numbers):
    even_sum = sum(n for n in numbers if n % 2 == 0)
    odd_sum = sum(n for n in numbers if n % 2 != 0)
    return even_sum, odd_sum

if __name__ == "__main__":
    nums = [3, 7, 10, 14, 21, 28]
    even, odd = sum_even_odd(nums)
    print(f"Sum of even numbers: {even}")
    print(f"Sum of odd numbers: {odd}")
