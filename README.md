# drupal-console-zh-hant
DrupalConsole Chinese Traditional Language / 繁體中文

# 繁體中文版本

## 使用說明

為 Drupal 8 安裝 Drupal Console 時，預設語言皆為英文。

要安裝 Drupal Console 繁體中文說明介面，請依照以下指令執行安裝工作。

```
$ composer require drupal/console-zh-hant
```

### 安裝 Drupal Console

請執行下列指令，為你的 Drupal 網站安裝相符版本的 Drupal Console。

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### 安裝 Drupal Console 啟動程式

Drupal Console 啟動程式是用來提供一個合適的 Drupal Console 版本給所有使用者，以避免與不同版本的 Drupal 發生相容性問題。要在 Drupal 8 網站下執行 Drupal 指令，您必須依照下列指示安裝全域的 Drupal Console 啟動程式。

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### 貢獻開源程式碼

如果你想要一起為此翻譯工作貢獻內容，你需要遵照以下步驟：

- 由此程式庫取得分支（ Fork ） [https://github.com/hechoendrupal/drupal-console-zh-hant#fork-destination-box](https://github.com/hechoendrupal/drupal-console-zh-hant#fork-destination-box) 。
- 複製分支的程式庫到本地機器。
- 設定上層來源（ upstream ）

為了取得其他貢獻者的最新翻譯，你必須利用以下 git 指令連結主要程式庫作為上層來源

```
$ git remote add upstream git@github.com:hechoendrupal/drupal-console-zh-hant.git
```

在開始工作之前，你必須執行下列指令取得最新的更新內容
```
$ git fetch upstream
$ git merge upstream/master
```

須知：為了避免與其他貢獻者提交的翻譯產生衝突，請上傳你當天最新的翻譯到你的分支程式庫並建立 PR

# English Version

Check instructions at [https://github.com/hechoendrupal/drupal-console-en](https://github.com/hechoendrupal/drupal-console-en)