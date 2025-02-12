# 軟體工程師必考題

## question
* 可以請您介紹一下自己嗎？
* 請問你的優點和缺點是什麼？
* 請問您離開上一份工作的原因是什麼？
* 履歷上的空窗期在做什麼？
* 為什麼想面試這份工作？ 對公司的了解？
* 工作中遇過最挫折的經驗是什麼？／最大的失敗是什麼？
* 如果一直達不到工作目標時，你會怎麼辦？
* 你對未來3~5年有什麼規劃？

* 介紹你參與過最成功的專案？ 你在其中的貢獻是什麼？
* 參與過最有挑戰的專案？ 如何克服難題？
* 你有哪些強項可以勝任這份工作？
* 工作發現錯誤時會怎麼解決？
* 你通常在團隊中扮演什麼樣的角色？ ...
* 你最熟悉哪些技術？
* 最近有學什麼新技術嗎？

* 你的期望待遇／預期薪資範圍是多少？」


* 你認識的前端框架，三大框架：React、Vue、Angular
* 物件導向程式設計(Object Oriented Programming)OOP  
  三大特性(封裝、繼承、多型)
* Restful API 是什麼？這樣設計有什麼好處？透過 HTTP method 的動詞，以及 CRUD action 設計的 API 規格  
  RESTful API 會是在講基於 HTTP 通訊協定上的介面服務設計。  
  RESTful API 會使用標準的 HTTP method 當作動詞來對資源進行操作  
  * GET: 取得資料
  * POST: 新增資料
  * PUT: 修改資料
  * DELETE: 刪除資料

## program

* 1~100找最大質數

* 氣泡排序法(Bubble Sort)
```
//氣泡排序法(Bubble Sort)
public static void BubbleSort(int[] list)
{
    int len = list.Length;
    for(int i = 1;i<=len-1;i++)//執行的回數
        for (int j = 1; j <= len - i; j++)//執行的次數
        {
            if (list[j] < list[j - 1])
            {
                //二數交換
                int temp = list[j];
                list[j] = list[j - 1];
                list[j - 1] = temp;
            }
        }
}
```

* script
```
<script>
document.write(5 + 6);
</script>

<script>
document.getElementById("demo").innerHTML = 5 + 6;
</script>
```