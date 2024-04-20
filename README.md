# What-To-Eat 今天吃什麼

## TODO
- [ ] class `Restaurant` and `Food`
- [ ] Deep Random
- [ ] csv file
- [ ] 飲料 vector
- [ ] 早/午/晚/宵 篩選

1.餐點清單
2.新增餐點
3.隨機選擇
4.選擇結果
5.錯誤處理

int main() {
    Restaurant restaurant("KFC");
    Restaurant restaurant("711");
    Restaurant restaurant("媽媽樂");
    Restaurant restaurant("花果山");
    Restaurant restaurant("好吃炒飯");

    restaurant.addFood(1, "Burger", 5.99);
    restaurant.addFood(2, "Pizza", 6.99);
    restaurant.addFood(3, "Salad", 3.99);
    restaurant.addFood(3, "french fries", 1.99);
    restaurant.addFood(3, "taco", 5.99);

    restaurant.printMenu();

    return 0;
}

Members:
- B2209239 黃郁鈞
- A9223218 陳彥杰
- A9251041 胡凱棠
