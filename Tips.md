# Thread  线程的相关问题

一.线程的生命周期:新建->就绪->运行->阻塞->死亡

二.实现线程的方式：1.继承Thread类
                  2.实现Runnable接口
                  3.实现Callable接口
                  4.线程池（ExecutorService）
                  
三.线程同步机制方式:1.lock
                  2.同步代码块（synchronized(){...}）
                  3.同步方法(例如：public void synchronized 方法名（）{...})
