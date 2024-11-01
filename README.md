- 👋 别天神之书

<!---
bietianshenzhishu/bietianshenzhishu is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
def print_pyramid(height):
    for i in range(height):
        # 打印空格
        print(' ' * (height - i - 1), end='')
        # 打印星号
        print('*' * (2 * i + 1))

# 设置金字塔的高度
pyramid_height = 5
print_pyramid(pyramid_height)
