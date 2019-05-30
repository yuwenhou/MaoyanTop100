## 爬虫爬取猫眼电影Top100的信息
### 主要步骤
#### 1.#获取网页的响应
    def get_one_page(url):
#### 2.#利用正则表达式匹配字符串
    def get_one_page(url):
#### 3.保存成txt
    def write_to_file(content):
#### 注意：用multiprocessing可以加快速度
    pool = Pool()
    pool.map(main,[i*10 for i in range(10)])