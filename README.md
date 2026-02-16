
def count_even_numbers(number):
    return sum(1 for n in numbers if n % 2 == 0)

if __name__ == "__main__":
    nums = [3, 8, 15, 22, 7, 10, 14]
    print(f"Numbers: {nums}")
    print(f"Even count: {count_even_numbers(nums)}")
