# Download_Sport_Album
Download_Sport_Album

# 瀏覽器Selenium操作放在背景執行的參數設定
from selenium.webdriver.chrome.options import Options
chrome_options = Options()
chrome_options.add_argument("--headless")  # 定義 headless
driver = webdriver.Chrome(chrome_options=chrome_options)
