---
description: TLS/SSL憑證有助於讓客戶 在您的網站上感受到安全 Tenten Basic TLS/SSL憑證提供安全 且靈活的加密。
---

# SSL 憑證相關常見問題

### SSL 憑證相關常見問題：

#### 為什麼 SSL 的效期會改變？

從 2020/9/1開始，SSL/TLS 憑證核發的上限將改為 13 個月 (397 天)。所有在此日期後購買的 SSL 憑證都會套用新的效期長度，在此之前購買的憑證則不受影響。更多資訊請見此篇[部落格文章](https://tenten.co/help/important-notification-about-ssl-offerings-9322)，文內將會詳細說明本次效期變更的情形及 Tenten 的回應方式。

#### 我要如何安裝 SSL 憑證？

您的 Tenten SSL 憑證成功核發後，我們會以 email 通知您。下一步則依據網站託管位置及購買憑證時所選擇的選項而定。

如果您選擇虛擬主機或建站神器，我們會為您處理所有作業。如果您透過其他公司或使用我們的 VPS 或專屬伺服器託管網站，[請至此瞭解更詳細的資訊](https://tenten.co/help/generate-a-csr-certificate-signing-request-5343)。

#### 什麼是 SSL 憑證，我為什麼需要這個憑證？

SSL 代表安全通訊端層，SSL 憑證可以顯示可供驗證網站擁有者的資訊，並用 SSL/TLS 加密網頁流量，包括公開金鑰、憑證核發商，以及相關子網域等。SSL 通常稱作 TLS，是一種可以加密網際網路流量及驗證伺服器身分的協定。所有使用 HTTPS 網址的網站都有使用 SSL/TLS。

想贏得使用者的信任，網站就需要擁有 SSL 憑證：您需要用它保護使用者資料安全、驗證網站所有權，並防止攻擊者假造您的網站。

驗證\
SSL 憑證可以驗證擁有網域的客戶。藉此防止網域攻擊或詐騙。

加密\
SSL/TLS 會藉由 SSL 憑證使用的公開及私密金鑰組合加密資訊。客戶會取得公開金鑰，並藉由伺服器的 SSL 憑證啟動 TLS 連線。

HTTPS\
HTTPS 網址一定要有 SSL 憑證才能使用。如果網站流量經過 SSL/TLS 加密，便會顯示 HTTPS (HTTP 的安全版本)。除了保護使用者資料之外，HTTPS 還可以加強網站訪客的信任感。

#### SSL 憑證有哪些類型？

SSL 憑證共有三種類型，Tenten 皆有提供。每種類型提供不同層級的安全性。如果需要處理個人使用者資料，那麼瞭解 SSL 憑證種類就十分重要了。

* \*\*網域驗證 (DV) SSL 憑證。\*\*DV 憑證可以驗證網站的擁有者。憑證頒發機構會向網站註冊的 email 地址發送驗證身分用的 email。公司無需提供詳細資訊，DV 憑證也是最容易取得的憑證，所以公信力也是最低等級。
* \*\*組織驗證 (OV) SSL 憑證。\*\*憑證頒發機構必須驗證組織、實際位置地址及網站的網域名稱。這項程序需要約 2-3 天的時間。OV 憑證有中等的公信力，適合以大眾為對象，並進行較低層級交易的網站。
* \*\*延伸驗證 (EV) SSL 憑證。\*\*這是安全性層級最高的 SSL 憑證，最適合需要處理敏感資訊的網站。憑證頒發機構需要仔細審核申請人身分之後才能核發 EV SSL 憑證，審核過程需要檢驗企業文件、確認身分，並需透過第三方資料庫驗證相關資訊。

#### 標準版 SSL 憑證與超豪版 SSL 憑證的差別是什麼？

所有受到 SSL 保護的網站會在網址列上顯示 https:// 前置字串。使用 Tenten 超豪版 EV SSL 憑證保護的網站會顯示綠色瀏覽器網址列，使訪客能夠迅速確定組織合法無虞，並已經由嚴格的業界標準證實此組織確實存在。

購買 Tenten 的超豪版 EV SSL 憑證後，便需進行最嚴謹的審查程序。我們藉由驗證依法登記的名稱、地址、電話與其他公司資訊，來驗證您對網域的控制權，以及公司的合法性。此程序大約需要 30 天，在此期間我們仍會確保您的安全。Tenten EV SSL 憑證附有一個免費的標準版 SSL，可供您在審查時使用，因此在等待驗證期間一樣能保護交易安全。

如需詳細資訊，請參閱[在企業網站使用超豪版延伸驗證 (EV) SSL 憑證，有哪些好處？](https://tenten.co/help/what-are-the-advantages-of-a-premium-extended-validation-ev-ssl-certificate-for-your-business-2201)

#### 我需要使用哪一種 SSL 憑證？

回答下列問題即可幫助您找到合乎需求的 SSL 憑證：

1.您的所在地點？

我們的憑證基本上是向全世界核發，但有一些地方例外。請看[此清單](https://tenten.co/help/which-countries-are-currently-supported-for-certificate-issuance-853)，查看您是否在清單上。

2.您的網站是商業網站還是個人網站？

除非您準備在個人網站上販售商品，不然標準版 SSL 憑證 (DV) 就夠好了，資訊商業網站也是一樣。電子商務網站應使用單一網域標準版 SSL 憑證 (DV) 或超豪版 SSL 憑證 (EV)。

3.您使用的是哪一種虛擬主機伺服器？

我們的 SSL 憑證在大多數主機和伺服器設定上均能正常運作。為了保護在 Microsoft’s Exchange Server 2007、Exchange Server 2010 或 Live® Communications Server 上多個網域的安全，請使用多網域 UCC SSL。

4.您需要保護幾個不同網域？

**萬用 SSL 憑證**可保護多個子網域。例如，使用萬用憑證即可保護 \*.coolexample.com 的安全，同時亦包含 shop.coolexample.com、www.coolexample.com 和其他子網域。

**UCC SSL 憑證**可保護多個網域、子網域與網站。例如，您可以保護 www.coolexample.com、mail.coolexample.com 與 www.awesomeexample.com 的安全。

5.您需要支援遠端 PC 管理 Intel vPro 技術的 SSL 憑證嗎？

您需要的是我們的 OV 豪華版憑證。

#### Tenten SSL 憑證核發需要多久時間？

標準版 Tenten SSL (DV) 最長通常只需要 5 分鐘。Tenten 豪華版 SSL (OV) 則需 3 至 5 個工作天，因為我們不僅需要驗證網域所有權，還需驗證位於 SSL 申請內容內的組織或企業網站是否實際存在。

Tenten 超豪版 (EV) 憑證則會透過詳實的申請內容進行更嚴謹的審查程序。在開始之前，請先收集與您企業相關的詳細資訊，例如註冊號碼、公司或註冊專員及其他相關的法律資訊。

#### 我該如何建立憑證簽名申請 (CSR)？

此舉是依據您在網路伺服器所使用的軟體而定。[瞭解更多資訊](https://tenten.co/help/generate-a-csr-certificate-signing-request-5343)。

如需進一步瞭解如何在 Plesk 控制面板、cPanel 與 Microsoft IIS 上產生 CSR，請[看這裡](https://tenten.co/help/generate-a-csr-certificate-signing-request-5343)。

#### 什麼是多網域 UC 憑證 / SAN憑證？

統一通訊憑證 (UCC) 是一種 SSL 憑證，用於保護多個網域名稱，以及一個網域名稱底下多個主機名稱的安全。UCC SSL 憑證讓您可以透過單一 SSL 憑證保護主要網域名稱以及最多 99 個其他主體別名 (SAN) 的安全。例如，您用一個 UCC 即可保護 www.domains1.com、www.domains2.net 與 www.domains3.org。

UCC 相容於共用主機並適用於 Microsoft® Exchange Server 2007、Exchange Server 2010 與 Microsoft Live® Communications Server。不過，網站簽章和憑證的「核發對象」資訊只會列出主要網域名稱。請注意，所有次要主機帳戶也會列在憑證範圍中，因此，如果您不想要讓網站看起來彼此「有關係」，請使用此類型憑證。

#### 我可以使用 HTTPS 保護幾個獨立網域？

根據網站的不同設定，您可能需要使用單一網域 SSL 以外的憑證。

* 萬用 SSL 憑證可以套用到網域名稱內所有子網域上。例如，您可以保護 \*.coolexample.com，同時還能保護 shop.coolexample.com、www.coolexample.com 及其他子網域。
* UCC SSL 憑證可保護多個子網域、唯一網域名稱和網站。例如，您可以保護 www.coolexample.com、mail.coolexample.com 與 www.awesomeexample.com 的安全。

#### 想進一步瞭解 SSL 憑證嗎？

請前往我們的[知識庫](https://tenten.co/help/ssl-certificates-1000006)進一步瞭解 SSL 憑證設定、使用與管理的相關資訊。
