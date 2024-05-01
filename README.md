# Producer-consumer pattern(AWS Simple Queue Service基礎概念）
將Producer和Consumer分開，Producer生產資源，Consumer消耗資源  
Producer和Consumer之間透過一個共享的資源來進行通訊  
達到Producer和Consumer之間解耦的目的，同時增進資源的調度效率

想像成餐廳的廚師和服務生，廚師(Producer)生產食物(Data)，將食物送到客人(Consumer)手上
餐廳有大小間、便當店、高級餐館、員工餐廳，每天餐廳的出餐效率、客人的接收率、客人排隊、餐廳容納量都不相同


# 多線程
wait() 等待  
notifyAll() 該線程結束後，釋放所有正在等待的線程，執行wait()之後的程式碼  
如果使用notify()，可能會導致其他線程永遠無法喚醒（lazy thread該線程只有wait但沒有notify出去的情況）  
synchronized method 保護共享資源  


# 參考:
Producer-consumer pattern:  
https://twmht.github.io/blog/posts/multithread/producer-consumer.html

多線程：  
https://blog.csdn.net/x541211190/article/details/109322537