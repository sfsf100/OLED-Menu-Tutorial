# OLED-Menu-Tutorial

## 硬體:
OLED_U8G 、OLED_GFX 都是ardunio和esp32專用的。
OLED 是stm32 。

Arduino 與OLED 之間使用I2C 通訊。
A4類比腳位 接SDA、 A5類比腳位 接SCL
OLED 選用 SSD1306。尺寸:   0.96吋：128x64

## 專案程式碼:
OLED_U8G : 使用 U8GLIB 庫  ，顯示OLED Menu。  
OLED_GFX : 使用 Adafruit 庫  ，顯示Hello word。  
參考至:https://sites.google.com/site/lakilch01/%E9%9B%B6%E7%B5%84%E4%BB%B6%E4%BB%8B%E7%B4%B9/oled


OLED : 是使用stm32 的相關庫  ，暫無。

OLED_GFX 和 U8GLIB 都是用於控制 OLED (Organic Light-Emitting Diode) 顯示器的庫，但它們有一些明顯的差異：

## 支援的硬體:

OLED_GFX: 通常支援基於 Adafruit 的 OLED 顯示器，如 Adafruit SSD1306 驅動的顯示器。
U8GLIB: 支援多種不同製造商的 OLED 顯示器，例如 SSD1306、SSD1309、SSD1327 等。它相對於硬體的支援更廣泛，可以適應不同的 OLED 顯示器。
##庫的選擇性:

OLED_GFX: 是 Adafruit 的庫，通常與 Adafruit 的其他庫和硬體良好地整合在一起。
U8GLIB: 這是由 Oliver Kraus 開發的庫，提供了更多的自定義和配置選項，使得它可以適應不同的應用需求。
程式碼的使用方式:

OLED_GFX: 使用比較簡單，可以輕鬆地與其他 Adafruit 的庫和硬體進行整合。
U8GLIB: 需要更多的配置和自定義，因此對於有經驗的使用者來說，提供了更大的靈活性和控制力。
性能和資源使用:

OLED_GFX: 通常會有更低的記憶體使用，並且在某些情況下，它可以提供更好的效能。
U8GLIB: 較老的版本可能會使用更多的記憶體，但近期的版本通常會優化這一點。
總結來說，希望有更多的自定義選項，U8GLIB 可能會是一個更好的選擇。
如果您使用的是 Adafruit 的硬體並且希望較為簡單地使用庫，那麼 OLED_GFX 可能更適合您。

|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |
