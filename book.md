# ISTQB® CTFL® v4.0.1 — Türkçe Deneme Sınavı 4

## Sınav hakkında

Bu çalışma, İngilizce Deneme Sınavı 4 esas alınarak hazırlanmıştır. Ders programına (syllabus) uygun kavramları Türkçe sorularla çalışabilirsiniz. Soru kökleri ve seçenekler önce İngilizce, hemen altında Türkçedir. Açıklamalar Türkçedir. 39 soruda dört seçenek ve tek doğru cevap; bir soruda beş seçenek ve tam iki doğru cevap vardır. Her soru 1 puandır; geçme çizgisi 26/40 (%65), standart süre 60 dakikadır.

**Süreyi doğru seçin.** TTB'nin Türkçe/İngilizce kitapçığıyla sınava giren ana dili Türkçe aday için süre 60 dakikadır. Ana dili Türkçe olmayan aday için TTB 75 dakika belirtir. Ek süre sınav dili ve sağlayıcı koşullarına bağlıdır. Sınava kaydolmadan önce [TTB'nin güncel koşullarını](https://www.turkishtestingboard.org/kayit/foundation-level-certified-tester/) kontrol edin.

| Bilişsel seviye | Soru |
|---|---:|
| K1 — Hatırlama | 8 |
| K2 — Anlama | 24 |
| K3 — Uygulama | 8 |

| Bölüm | Soru |
|---|---:|
| 1 — Yazılım testinin temelleri | 8 |
| 2 — Yaşam döngüsü boyunca test | 6 |
| 3 — Statik test | 4 |
| 4 — Test analizi ve tasarımı | 11 |
| 5 — Test aktivitelerinin yönetimi | 9 |
| 6 — Test araçları | 2 |

### Nasıl kullanılır?

Gerçek sınav provası için 60 dakikalık, kesintisiz bir oturum ayırın. Ek süre hakkınız varsa 75 dakika seçin; 75 dakikayı bir çalışma süresi olarak da kullanabilirsiniz, ancak bunu 60 dakikalık prova sonucuyla aynı ölçüm saymayın. Sorular sınav provası için karışık sıradadır; bölüm başlıklarına göre gruplanmamıştır. Cevaplara bakmadan 40 soruyu tamamlayın, Part 2 ile puanlayın, ardından Part 3 ile yanlışların nedenlerini inceleyin.

Tek seçimli sorularda bir seçenek, iki seçimli soruda tam iki seçenek işaretleyin. İki seçimli soru da 1 puandır; kısmi puan verilmez. Yanlış veya boş cevap 0 puandır; yanlışlar doğruları götürmez. K3 sorular için yaklaşık üçer dakika ayırmak bir çalışma önerisidir; bütün sınavın toplam süresini de gözetin.

### Dört tuzak

- **Kaynak bilgi eksiği:** Ders programındaki bir kavramı, tanımı veya listeyi hatırlayamama. İlgili bölümü yeniden çalışın.
- **Near-miss karışıklığı:** Komşu kavramları birbirinin yerine koyma; örneğin onaylama ve regresyon testi. Ayırt edici amaçlarını karşılaştırın.
- **Prosedür hatası:** Bir tekniği uygularken yanlış adım, varyant veya hesap kullanma. Çözümü adım adım yeniden kurun.
- **Dikkatsiz okuma:** Kökün yönlendirmesini veya verisini kaçırma. **EN İYİ** ve **DEĞİLDİR** gibi yön sözcüklerini kontrol edin.

Bu dört etiket sorunun genel tuzağını gösterir. Kılavuzdaki çeldirici adları ise tek bir yanlış seçeneğin neden cazip olduğunu açıklar; iki sınıflandırma farklı amaçlara hizmet eder.

**Bağımsızlık ve lisans.** ISTQB® ve CTFL® tescilli markalardır. Bu çalışma ISTQB veya TTB tarafından onaylanmamıştır ve bu kuruluşların resmî sınavı değildir. © 2026 Kadir Çamoğlu. Özgün içerik [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) ile paylaşılır; ISTQB'ye ait alıntılar, LO kodları, ilke adları ve markalar bu lisansın dışındadır.


## Part 1 — Sorular

Cevap anahtarını açmadan önce bütün soruları tamamlayın.

### S1–S10



**Soru 1** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>An alert service uses the full decision table below. T and F mean true and false. The team wants to merge R1 and R2 into one rule without changing the behavior.</p>
<div class="table-wrap"><table style="width:100%;">
<colgroup>
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<thead>
<tr>
<th>Condition / action</th>
<th>R1</th>
<th>R2</th>
<th>R3</th>
<th>R4</th>
<th>R5</th>
<th>R6</th>
<th>R7</th>
<th>R8</th>
</tr>
</thead>
<tbody>
<tr>
<td>Account active</td>
<td>T</td>
<td>T</td>
<td>T</td>
<td>T</td>
<td>F</td>
<td>F</td>
<td>F</td>
<td>F</td>
</tr>
<tr>
<td>Alert urgent</td>
<td>T</td>
<td>T</td>
<td>F</td>
<td>F</td>
<td>T</td>
<td>T</td>
<td>F</td>
<td>F</td>
</tr>
<tr>
<td>Subscribed</td>
<td>T</td>
<td>F</td>
<td>T</td>
<td>F</td>
<td>T</td>
<td>F</td>
<td>T</td>
<td>F</td>
</tr>
<tr>
<td>Result</td>
<td>Send</td>
<td>Send</td>
<td>Send</td>
<td>Suppress</td>
<td>Suppress</td>
<td>Suppress</td>
<td>Suppress</td>
<td>Suppress</td>
</tr>
</tbody>
</table></div>
<p>Which merged rule replaces exactly R1 and R2? A dash means that either value is accepted.</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir uyarı servisi aşağıdaki tam karar tablosunu kullanır. D ve Y, doğru ve yanlış anlamındadır. Ekip davranışı değiştirmeden R1 ve R2'yi tek kuralda birleştirmek ister.

| Koşul / eylem | R1 | R2 | R3 | R4 | R5 | R6 | R7 | R8 |
|---|---|---|---|---|---|---|---|---|
| Hesap aktif | D | D | D | D | Y | Y | Y | Y |
| Uyarı acil | D | D | Y | Y | D | D | Y | Y |
| Abone | D | Y | D | Y | D | Y | D | Y |
| Sonuç | Gönder | Gönder | Gönder | Gönderme | Gönderme | Gönderme | Gönderme | Gönderme |

Hangi birleşik kural tam olarak R1 ve R2'nin yerini alır? Çizgi (–), iki değerin de kabul edildiğini gösterir.

</div>

a) <span lang="en">Active = T, urgent = –, subscribed = T; result = Send</span><br><span lang="tr">Aktif = D, acil = –, abone = D; sonuç = Gönder</span>

b) <span lang="en">Active = –, urgent = T, subscribed = –; result = Send</span><br><span lang="tr">Aktif = –, acil = D, abone = –; sonuç = Gönder</span>

c) <span lang="en">Active = T, urgent = T, subscribed = –; result = Send</span><br><span lang="tr">Aktif = D, acil = D, abone = –; sonuç = Gönder</span>

d) <span lang="en">Active = T, urgent = –, subscribed = –; result = Send</span><br><span lang="tr">Aktif = D, acil = –, abone = –; sonuç = Gönder</span>

Bir seçenek seçin.



**Soru 2** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Every week, the test lead compares the actual test progress against the test plan, and when execution falls behind, re-prioritizes the remaining tests and requests an additional tester. Which test activity is the test lead performing?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Test lideri her hafta gerçekleşen test ilerlemesini test planıyla karşılaştırır. Test koşumu geride kaldığında kalan testleri yeniden önceliklendirir ve ek bir test uzmanı talep eder. Test lideri hangi test aktivitesini yürütmektedir?

</div>

a) <span lang="en">The test planning activity</span><br><span lang="tr">Test planlama aktivitesi</span>

b) <span lang="en">The test analysis activity</span><br><span lang="tr">Test analizi aktivitesi</span>

c) <span lang="en">The test implementation activity</span><br><span lang="tr">Test uyarlama aktivitesi</span>

d) <span lang="en">Test monitoring and control</span><br><span lang="tr">Test gözetimi ve kontrolü</span>

Bir seçenek seçin.



**Soru 3** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A team is assessing risks before automating tests. Which TWO proposals expose the team to automation risks? Select the two risks described by the proposals.</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir ekip test otomasyonuna geçmeden önce riskleri değerlendirir. Hangi **İKİ** öneri ekibi otomasyon riskleriyle karşı karşıya bırakır? Önerilerin anlattığı iki riski seçin.

</div>

a) <span lang="en">Measure coverage to identify behavior that needs additional tests and human assessment</span><br><span lang="tr">Ek test ve insan değerlendirmesi gerektiren davranışları belirlemek için kapsamı ölçmek</span>

b) <span lang="en">Cancel exploratory testing because a passing automated suite is treated as complete assurance</span><br><span lang="tr">Geçen otomatik test takımı tam güvence sayıldığı için keşif testini iptal etmek</span>

c) <span lang="en">Review the effort required to maintain the automated scripts when the application changes</span><br><span lang="tr">Uygulama değiştiğinde otomatik betiklerin bakımı için gereken eforu değerlendirmek</span>

d) <span lang="en">Compare failures with logs before deciding whether the product or a test script is faulty</span><br><span lang="tr">Ürünün mü, betiğin mi hatalı olduğuna karar vermeden arızaları kayıtlarla karşılaştırmak</span>

e) <span lang="en">Commit to a framework without checking its compatibility with the target platforms</span><br><span lang="tr">Hedef platformlarla uyumluluğunu kontrol etmeden bir yazılım çatısına bağlanmak</span>

**İKİ seçenek seçin.**



**Soru 4** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A document workflow starts in Draft. Its complete transitions are: Draft —submit→ Review; Review —reject→ Draft; Review —approve→ Approved; Approved —archive→ Archived. No other transitions are defined.</p>
<figure>
<img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzNDAiIGhlaWdodD0iNDQwIiB2aWV3Qm94PSIwIDAgMzQwIDQ0MCIgcm9sZT0iaW1nIiBhcmlhLWxhYmVsbGVkYnk9InRpdGxlIGRlc2MiPg0KPHRpdGxlIGlkPSJ0aXRsZSI+RG9jdW1lbnQgd29ya2Zsb3c8L3RpdGxlPjxkZXNjIGlkPSJkZXNjIj5EcmFmdCB0byBSZXZpZXcgb24gc3VibWl0LiBSZXZpZXcgdG8gRHJhZnQgb24gcmVqZWN0LiBSZXZpZXcgdG8gQXBwcm92ZWQgb24gYXBwcm92ZS4gQXBwcm92ZWQgdG8gQXJjaGl2ZWQgb24gYXJjaGl2ZS4gSW5pdGlhbCBzdGF0ZSBEcmFmdC48L2Rlc2M+DQo8ZGVmcz48bWFya2VyIGlkPSJhcnJvdyIgbWFya2VyV2lkdGg9IjgiIG1hcmtlckhlaWdodD0iOCIgcmVmWD0iNyIgcmVmWT0iNCIgb3JpZW50PSJhdXRvIj48cGF0aCBkPSJNMCAwIEw4IDQgTDAgOFoiIGZpbGw9IiMyNTQ5NjIiLz48L21hcmtlcj48L2RlZnM+DQo8cmVjdCB3aWR0aD0iMzQwIiBoZWlnaHQ9IjQ0MCIgcng9IjEyIiBmaWxsPSIjZjRmOGZhIi8+DQo8ZyBmaWxsPSIjZmZmZmZmIiBzdHJva2U9IiMyNTQ5NjIiIHN0cm9rZS13aWR0aD0iMiI+DQo8cmVjdCB4PSIxMDYiIHk9IjQzIiB3aWR0aD0iMTQ1IiBoZWlnaHQ9IjQ4IiByeD0iMTAiLz4NCjxyZWN0IHg9IjEwNiIgeT0iMTQ1IiB3aWR0aD0iMTQ1IiBoZWlnaHQ9IjQ4IiByeD0iMTAiLz4NCjxyZWN0IHg9IjEwNiIgeT0iMjQ3IiB3aWR0aD0iMTQ1IiBoZWlnaHQ9IjQ4IiByeD0iMTAiLz4NCjxyZWN0IHg9IjEwNiIgeT0iMzQ5IiB3aWR0aD0iMTQ1IiBoZWlnaHQ9IjQ4IiByeD0iMTAiLz4NCjwvZz4NCjxnIGZvbnQtZmFtaWx5PSJBcmlhbCwgc2Fucy1zZXJpZiIgZm9udC1zaXplPSIxOSIgZmlsbD0iIzE5Mzk0ZSIgdGV4dC1hbmNob3I9Im1pZGRsZSI+DQo8dGV4dCB4PSIxNzgiIHk9Ijc0Ij5EcmFmdDwvdGV4dD48dGV4dCB4PSIxNzgiIHk9IjE3NiI+UmV2aWV3PC90ZXh0Pjx0ZXh0IHg9IjE3OCIgeT0iMjc4Ij5BcHByb3ZlZDwvdGV4dD48dGV4dCB4PSIxNzgiIHk9IjM4MCI+QXJjaGl2ZWQ8L3RleHQ+DQo8L2c+DQo8ZyBmaWxsPSJub25lIiBzdHJva2U9IiMyNTQ5NjIiIHN0cm9rZS13aWR0aD0iMiIgbWFya2VyLWVuZD0idXJsKCNhcnJvdykiPg0KPHBhdGggZD0iTTE3OCAyM1Y0MCIvPjxwYXRoIGQ9Ik0xNzggOTNWMTQxIi8+PHBhdGggZD0iTTE3OCAxOTVWMjQzIi8+PHBhdGggZD0iTTE3OCAyOTdWMzQ1Ii8+DQo8cGF0aCBkPSJNMTA0IDE2OUg2NFY2N0gxMDEiLz4NCjwvZz48Y2lyY2xlIGN4PSIxNzgiIGN5PSIxNyIgcj0iNiIgZmlsbD0iIzI1NDk2MiIvPg0KPGcgZm9udC1mYW1pbHk9IkFyaWFsLCBzYW5zLXNlcmlmIiBmb250LXNpemU9IjE2IiBmaWxsPSIjMTkzOTRlIj4NCjx0ZXh0IHg9IjE5MiIgeT0iMTIzIj5zdWJtaXQ8L3RleHQ+PHRleHQgeD0iMTkyIiB5PSIyMjUiPmFwcHJvdmU8L3RleHQ+PHRleHQgeD0iMTkyIiB5PSIzMjciPmFyY2hpdmU8L3RleHQ+PHRleHQgeD0iMTUiIHk9IjEyNCI+cmVqZWN0PC90ZXh0Pg0KPC9nPjwvc3ZnPg==" alt="Document workflow: Draft to Review by submit; Review to Draft by reject; Review to Approved by approve; Approved to Archived by archive." />
<figcaption aria-hidden="true">Document workflow: Draft to Review by submit; Review to Draft by reject; Review to Approved by approve; Approved to Archived by archive.</figcaption>
</figure>
<p>After which event sequence is the document in Review?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir belge iş akışı Taslak durumunda başlar. Tanımlanmış bütün geçişler şunlardır: Taslak —gönder→ İnceleme; İnceleme —reddet→ Taslak; İnceleme —onayla→ Onaylandı; Onaylandı —arşivle→ Arşivlendi. Başka geçiş tanımlı değildir.

| Başlangıç durumu | Olay | Sonraki durum |
|---|---|---|
| Taslak | gönder | İnceleme |
| İnceleme | reddet | Taslak |
| İnceleme | onayla | Onaylandı |
| Onaylandı | arşivle | Arşivlendi |

Hangi olay dizisinden sonra belge İnceleme durumundadır?

</div>

a) <span lang="en">submit, approve</span><br><span lang="tr">gönder, onayla</span>

b) <span lang="en">submit, reject, submit</span><br><span lang="tr">gönder, reddet, gönder</span>

c) <span lang="en">submit, reject</span><br><span lang="tr">gönder, reddet</span>

d) <span lang="en">submit, approve, archive</span><br><span lang="tr">gönder, onayla, arşivle</span>

Bir seçenek seçin.



**Soru 5** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A test report refers to "the payment specification". Two approved versions of that document coexist, and the report does not say which one supplied the expected results. How should configuration management improve the report?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir test raporu “ödeme şartnamesi”ne atıf yapar. Belgenin iki onaylı sürümü aynı anda kullanımdadır; rapor beklenen sonuçların hangi sürüme dayandığını belirtmez. Yapılandırma yönetimi raporu nasıl iyileştirmelidir?

</div>

a) <span lang="en">Replace the document reference with the number of defects found during the run</span><br><span lang="tr">Belge atfını koşumda bulunan hata sayısıyla değiştirmek</span>

b) <span lang="en">Reference the specific controlled specification version used as the test basis</span><br><span lang="tr">Test esasına kaynak olan kontrollü şartname sürümünü belirtmek</span>

c) <span lang="en">Keep the generic document title and add the date the report was distributed</span><br><span lang="tr">Genel belge başlığını koruyup raporun dağıtıldığı tarihi eklemek</span>

d) <span lang="en">Replace the document reference with the severity of the highest open defect</span><br><span lang="tr">Belge atfını en yüksek açık hatanın önem derecesiyle değiştirmek</span>

Bir seçenek seçin.



**Soru 6** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A project reviews a short interface description and a large safety analysis using the same rigid meeting format. Reviewers report that neither discussion serves its purpose. Which change addresses the review success factor at issue?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir projede kısa bir arayüz açıklamasıyla geniş bir emniyet analizi aynı katı toplantı biçimiyle gözden geçirilir. Gözden geçiriciler iki tartışmanın da amacına hizmet etmediğini bildirir. Hangi değişiklik ilgili gözden geçirme başarı faktörünü ele alır?

</div>

a) <span lang="en">Keep the same review type for all work products to preserve procedural consistency</span><br><span lang="tr">Süreç tutarlılığı için bütün iş ürünlerinde aynı gözden geçirme türünü korumak</span>

b) <span lang="en">Evaluate reviewers by the number of disagreements they raise during each meeting</span><br><span lang="tr">Gözden geçiricileri her toplantıda dile getirdikleri anlaşmazlık sayısına göre değerlendirmek</span>

c) <span lang="en">Replace individual preparation with a longer meeting for every work product</span><br><span lang="tr">Her iş ürününde bireysel hazırlığın yerine daha uzun bir toplantı koymak</span>

d) <span lang="en">Choose review types suited to the objectives, work products and participants</span><br><span lang="tr">Hedeflere, iş ürünlerine ve katılımcılara uygun gözden geçirme türlerini seçmek</span>

Bir seçenek seçin.



**Soru 7** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>At release planning, testers propose that the team clarify acceptance conditions while discussing candidate user stories. A developer says this must wait until iteration tasks are assigned. Which response is appropriate?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Sürüm planlamasında test uzmanları, aday kullanıcı hikayeleri konuşulurken kabul koşullarının netleştirilmesini önerir. Bir geliştirici bunun döngü görevleri atanana kadar beklemesi gerektiğini söyler. Hangi yanıt uygundur?

</div>

a) <span lang="en">Testers can help write testable stories and acceptance criteria during release planning</span><br><span lang="tr">Test uzmanları sürüm planlamasında test edilebilir hikayelerin ve kabul kriterlerinin yazılmasına yardım edebilir.</span>

b) <span lang="en">Testers must postpone acceptance criteria for stories until the iteration's test execution has finished</span><br><span lang="tr">Test uzmanları hikayelerin kabul kriterlerini döngünün test koşumu tamamlanana kadar ertelemelidir.</span>

c) <span lang="en">Testers should replace release planning with the detailed testing tasks for one iteration</span><br><span lang="tr">Test uzmanları sürüm planlamasının yerine bir döngünün ayrıntılı test görevlerini koymalıdır.</span>

d) <span lang="en">Testers can contribute to release planning by reporting the final release's executed test results</span><br><span lang="tr">Test uzmanları son sürümün koşulmuş test sonuçlarını bildirerek sürüm planlamasına katkı verebilir.</span>

Bir seçenek seçin.



**Soru 8** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>What do TDD, ATDD and BDD have in common?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

TDD, ATDD ve BDD yaklaşımlarının ortak özelliği nedir?

</div>

a) <span lang="en">Tests are defined before the code that satisfies them is written</span><br><span lang="tr">Testler, onları karşılayan kod yazılmadan önce tanımlanır.</span>

b) <span lang="en">They all require a test automation framework to be in place</span><br><span lang="tr">Üçü de kurulmuş bir test otomasyon çatısını gerektirir.</span>

c) <span lang="en">They all express their tests in the Given/When/Then format</span><br><span lang="tr">Üçü de testlerini Given/When/Then biçiminde ifade eder.</span>

d) <span lang="en">They all start from the source code and derive tests from its structure</span><br><span lang="tr">Üçü de kaynak koddan başlayıp testleri onun yapısından türetir.</span>

Bir seçenek seçin.



**Soru 9** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A team uses three-point estimation for a test activity. The optimistic estimate is 7 person-hours, the most likely estimate is 13, and the pessimistic estimate is 31. The team allocates the weighted expected effort plus one standard deviation. What effort should it allocate?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir ekip test aktivitesi için üç noktalı tahminleme kullanır. İyimser tahmin 7 kişi-saat, en olası tahmin 13, kötümser tahmin 31’dir. Ekip, ağırlıklı beklenen efora bir standart sapma ekleyerek kaynak ayırır. Kaç kişi-saat ayırmalıdır?

</div>

a) <span lang="en">15 person-hours</span><br><span lang="tr">15 kişi-saat</span>

b) <span lang="en">19 person-hours</span><br><span lang="tr">19 kişi-saat</span>

c) <span lang="en">23 person-hours</span><br><span lang="tr">23 kişi-saat</span>

d) <span lang="en">21 person-hours</span><br><span lang="tr">21 kişi-saat</span>

Bir seçenek seçin.



**Soru 10** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Late in the release, specialists run load tests against the completed system, probe it for security weaknesses and measure response times against the service targets. None of these results guide feature development; they judge the finished product from a technical standpoint. Which testing quadrant is this?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Sürümün sonlarına doğru uzmanlar tamamlanmış sistemde yük testleri koşar, güvenlik zayıflıklarını araştırır ve yanıt sürelerini hizmet hedefleriyle karşılaştırır. Bu sonuçlar özelliklerin geliştirilmesine yön vermez; bitmiş ürünü teknik açıdan değerlendirir. Bu hangi test çeyreğidir?

</div>

a) <span lang="en">Q1 — technology-facing, support the team</span><br><span lang="tr">Q1 — teknoloji odaklı, ekibi destekler</span>

b) <span lang="en">Q2 — business-facing, support the team</span><br><span lang="tr">Q2 — iş odaklı, ekibi destekler</span>

c) <span lang="en">Q3 — business-facing, critique the product</span><br><span lang="tr">Q3 — iş odaklı, ürünü eleştirir</span>

d) <span lang="en">Q4 — technology-facing, critique the product</span><br><span lang="tr">Q4 — teknoloji odaklı, ürünü eleştirir</span>

Bir seçenek seçin.


### S11–S20



**Soru 11** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A test level has met its planned coverage target and has no unresolved defects above the agreed limit. The environment and test basis were available before testing began. Which statement correctly uses these facts in a completion decision?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir test seviyesi planlanan kapsam hedefine ulaşmıştır ve üzerinde anlaşılmış sınırın üzerinde çözümlenmemiş hata yoktur. Ortam ve test esası test başlamadan önce hazırdır. Hangi ifade bu bilgileri tamamlama kararında doğru kullanır?

</div>

a) <span lang="en">Environment availability is the achieved test thoroughness needed to justify completion</span><br><span lang="tr">Ortamın hazır olması, tamamlamayı gerekçelendiren ulaşılmış test derinliğidir.</span>

b) <span lang="en">Coverage and unresolved-defect thresholds are exit evidence; earlier availability supported entry</span><br><span lang="tr">Kapsam ve çözümlenmemiş hata eşikleri çıkış kanıtıdır; önceden hazır olma girişi desteklemiştir.</span>

c) <span lang="en">Test-basis availability replaces the coverage target when deciding whether testing is complete</span><br><span lang="tr">Test esasının hazır olması, tamamlamaya karar verirken kapsam hedefinin yerini alır.</span>

d) <span lang="en">An approved budget is stronger exit evidence than achieved coverage and residual defects</span><br><span lang="tr">Onaylı bütçe, ulaşılan kapsam ve kalan hatalardan daha güçlü çıkış kanıtıdır.</span>

Bir seçenek seçin.



**Soru 12** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>An integer batch-size field has three ordered partitions: values below 80 are rejected, 80 through 82 are accepted, and values above 82 are rejected. Using 2-value BVA, a tester has run 79, 80, 82 and 83. What boundary coverage has been achieved?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir tamsayı parti büyüklüğü alanının sıralı üç payı vardır: 80 altı reddedilir, 80–82 dahil kabul edilir, 82 üzeri reddedilir. Test uzmanı **2 değerli sınır değer analizi (SDA)** kullanarak 79, 80, 82 ve 83 değerlerini koşmuştur. Hangi sınır kapsamı sağlanmıştır?

</div>

a) <span lang="en">50%, because the two invalid partitions are excluded from boundary coverage</span><br><span lang="tr">%50; çünkü iki geçersiz pay sınır kapsamının dışında bırakılır.</span>

b) <span lang="en">About 57%, because coverage is calculated against the larger 3-value BVA set</span><br><span lang="tr">Yaklaşık %57; çünkü kapsam daha büyük 3 değerli SDA kümesine göre hesaplanır.</span>

c) <span lang="en">100%, because both adjacent-partition boundary pairs have been exercised</span><br><span lang="tr">%100; çünkü bitişik paylardaki her iki sınır çifti de sınanmıştır.</span>

d) <span lang="en">80%, because the accepted interval contains an additional integer value</span><br><span lang="tr">%80; çünkü kabul edilen aralıkta bir tamsayı daha vardır.</span>

Bir seçenek seçin.



**Soru 13** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A small team assigns one person to both test management and testing. Another team divides test management responsibilities among several people. A reviewer rejects both arrangements because each role must correspond to exactly one person. How should this claim be assessed?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Küçük bir ekip, bir kişiye hem test yönetimi hem test rolünü verir. Başka bir ekip test yönetimi sorumluluklarını birkaç kişi arasında paylaştırır. Bir gözden geçirici, her rolün tam bir kişiye karşılık gelmesi gerektiğini söyleyerek iki düzenlemeyi de reddeder. Bu iddia nasıl değerlendirilmelidir?

</div>

a) <span lang="en">It is correct: a role must have one exclusive owner for every activity</span><br><span lang="tr">Doğrudur; her aktivitede bir rolün kendisine ayrılmış tek sahibi olmalıdır.</span>

b) <span lang="en">It is incorrect: roles group responsibilities and can be combined or distributed</span><br><span lang="tr">Yanlıştır; roller sorumluluk gruplarıdır ve birleştirilebilir ya da paylaştırılabilir.</span>

c) <span lang="en">It is correct for the small team, but responsibilities may be split in the other</span><br><span lang="tr">Küçük ekip için doğrudur; diğer ekipte ise sorumluluklar paylaştırılabilir.</span>

d) <span lang="en">It is incorrect because test management and testing are interchangeable roles</span><br><span lang="tr">Yanlıştır; çünkü test yönetimi ve test birbirinin yerine geçen rollerdir.</span>

Bir seçenek seçin.



**Soru 14** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A print shop accepts the following criterion: "An order can be cancelled without a handling fee at least 36 hours before its scheduled collection. A later cancellation incurs the handling fee."</p>
<p>Collection is scheduled for Wednesday 21 October 2026 at 14:00. Which test case correctly checks a cancellation that incurs the fee?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir basımevi şu kabul kriterini kullanır: “Sipariş, planlanan teslim alma zamanından en az 36 saat önce iptal edilirse işlem ücreti alınmaz. Daha geç iptalde işlem ücreti uygulanır.”

Teslim alma zamanı 21 Ekim 2026 Çarşamba saat 14.00'tür. Hangi test senaryosu ücret uygulanacak bir iptali doğru kontrol eder?

</div>

a) <span lang="en">Cancel Tuesday 20 October at 01:00; expect the handling fee</span><br><span lang="tr">20 Ekim Salı saat 01.00’de iptal et; işlem ücreti bekle.</span>

b) <span lang="en">Cancel Tuesday 20 October at 03:00; expect no handling fee</span><br><span lang="tr">20 Ekim Salı saat 03.00’te iptal et; işlem ücreti alınmamasını bekle.</span>

c) <span lang="en">Cancel Tuesday 20 October at 02:00; expect the handling fee</span><br><span lang="tr">20 Ekim Salı saat 02.00’de iptal et; işlem ücreti bekle.</span>

d) <span lang="en">Cancel Tuesday 20 October at 03:00; expect the handling fee</span><br><span lang="tr">20 Ekim Salı saat 03.00’te iptal et; işlem ücreti bekle.</span>

Bir seçenek seçin.



**Soru 15** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Developers say that component tests written by their colleagues already count as fully independent external testing. A separate testing organization is also involved. Which assessment explains the difference?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Geliştiriciler, çalışma arkadaşlarının yazdığı bileşen testlerinin bütünüyle bağımsız dış test sayıldığını söyler. Çalışmaya ayrı bir test kuruluşu da katılmaktadır. Hangi değerlendirme aradaki farkı açıklar?

</div>

a) <span lang="en">Colleagues and a separate organization offer the same independence because neither wrote the code</span><br><span lang="tr">Kodu ikisi de yazmadığından çalışma arkadaşları ve ayrı kuruluş aynı bağımsızlığı sağlar.</span>

b) <span lang="en">Colleagues offer greater independence because they can consult the author during testing</span><br><span lang="tr">Test sırasında yazara danışabildiklerinden çalışma arkadaşları daha fazla bağımsızlık sağlar.</span>

c) <span lang="en">A separate organization has less independence because its testers lack the internal code history</span><br><span lang="tr">İç kod geçmişini bilmediklerinden ayrı kuruluşun test uzmanları daha az bağımsızdır.</span>

d) <span lang="en">Colleagues offer some independence, while a separate organization offers a higher degree</span><br><span lang="tr">Çalışma arkadaşları bir ölçüde bağımsızdır; ayrı kuruluş daha yüksek bağımsızlık sağlar.</span>

Bir seçenek seçin.



**Soru 16** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A test charter specifies "explore interrupted uploads for 45 minutes" without prescribing the sequence of clicks. A reviewer rejects it as incomplete because it lacks a fixed procedure. Which assessment fits session-based exploratory testing?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir test başlatma belgesi “kesilen yüklemeleri 45 dakika araştırın” der; tıklama sırasını belirtmez. Bir gözden geçirici, sabit prosedürü olmadığı için belgeyi eksik bulur. Hangi değerlendirme oturuma dayalı keşif testine uygundur?

</div>

a) <span lang="en">The rejection is justified because every test charter must specify all execution steps</span><br><span lang="tr">Her test başlatma belgesi bütün koşum adımlarını belirtmek zorunda olduğundan ret haklıdır.</span>

b) <span lang="en">The charter can guide the objectives and time-box while leaving test design to the tester</span><br><span lang="tr">Belge hedefleri ve süre sınırını yönlendirebilir; test tasarımını test uzmanına bırakabilir.</span>

c) <span lang="en">The rejection is justified because a time-box is used for scripted testing rather than exploration</span><br><span lang="tr">Süre sınırı keşif yerine betikli testte kullanıldığı için ret haklıdır.</span>

d) <span lang="en">The charter must be replaced by a statement-coverage target before the session can begin</span><br><span lang="tr">Oturum başlamadan belge yerine bir komut kapsamı hedefi konulmalıdır.</span>

Bir seçenek seçin.



**Soru 17** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Which statement about testing and quality management is correct?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Test ve kalite yönetimiyle ilgili hangi ifade doğrudur?

</div>

a) <span lang="en">Testing is a form of quality control, and QC and QA are both part of quality management</span><br><span lang="tr">Test kalite kontrolün bir biçimidir; kontrol ve güvence kalite yönetiminin parçalarıdır.</span>

b) <span lang="en">Quality management is one of the several activities that make up the test process</span><br><span lang="tr">Kalite yönetimi, test sürecini oluşturan çeşitli aktivitelerden biridir.</span>

c) <span lang="en">QA is a form of quality control that concentrates on the quality of the product</span><br><span lang="tr">Kalite güvencesi, ürünün kalitesine odaklanan bir kalite kontrol biçimidir.</span>

d) <span lang="en">Testing belongs to quality management, while QA is positioned outside of it</span><br><span lang="tr">Test kalite yönetimine dahildir; kalite güvencesi ise onun dışında yer alır.</span>

Bir seçenek seçin.



**Soru 18** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Under the whole team approach, what determines whether a team member can perform a particular task?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Tüm ekip yaklaşımında (whole team approach), bir ekip üyesinin belirli bir görevi yapabilmesini ne belirler?

</div>

a) <span lang="en">The member's original job title, regardless of their relevant knowledge</span><br><span lang="tr">İlgili bilgisinden bağımsız olarak üyenin başlangıçtaki görev unvanı</span>

b) <span lang="en">The member's location in a separate testing organization</span><br><span lang="tr">Üyenin ayrı bir test kuruluşunda bulunması</span>

c) <span lang="en">The member's seniority relative to the other team members</span><br><span lang="tr">Üyenin diğer ekip üyelerine göre kıdemi</span>

d) <span lang="en">The member's necessary knowledge and skills for that task</span><br><span lang="tr">Üyenin görev için gerekli bilgi ve becerilere sahip olması</span>

Bir seçenek seçin.



**Soru 19** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Complete BOTH statements about good testing practices that apply across SDLC models.</p>
<ol type="1">
<li>Test analysis and test design for a level begin _____.</li>
<li>Testers start reviewing work products _____.</li>
</ol>
<p>Which pair completes the statements correctly?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Yazılım geliştirme yaşam döngüsü modellerinin tümünde geçerli iyi test uygulamalarıyla ilgili **İKİ** ifadeyi de tamamlayın.

1. Bir test seviyesinin test analizi ve test tasarımı _____ başlar.
2. Test uzmanları iş ürünlerini gözden geçirmeye _____ başlar.

Hangi çift ifadeleri doğru tamamlar?

</div>

a) <span lang="en">During test execution; when approved final versions are available</span><br><span lang="tr">Test koşumu sırasında; onaylanmış son sürümler hazır olduğunda</span>

b) <span lang="en">During test completion; when the corresponding code has been released</span><br><span lang="tr">Test tamamlama sırasında; ilgili kod yayımlandığında</span>

c) <span lang="en">During the corresponding development phase; when draft versions are available</span><br><span lang="tr">İlgili geliştirme aşamasında; taslak sürümler hazır olduğunda</span>

d) <span lang="en">During test execution; when draft versions are available</span><br><span lang="tr">Test koşumu sırasında; taslak sürümler hazır olduğunda</span>

Bir seçenek seçin.



**Soru 20** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A loyalty program lets customers redeem 1 to 500 points per order: redemptions of 1–100 points get no bonus, redemptions of 101–500 points get a 5% bonus, and amounts of 0 or less, or more than 500, are rejected. Which set of test values covers every equivalence partition exactly once?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir sadakat programı müşterilerin sipariş başına 1–500 puan kullanmasına izin verir. 1–100 puan için bonus verilmez; 101–500 puan için %5 bonus verilir. 0 veya altındaki ve 500 üzerindeki miktarlar reddedilir. Hangi test değeri kümesi her denklik payını **tam bir kez** kapsar?

</div>

a) <span lang="en">0, 50, 250, 600</span><br><span lang="tr">0, 50, 250, 600</span>

b) <span lang="en">50, 250</span><br><span lang="tr">50, 250</span>

c) <span lang="en">0, 600</span><br><span lang="tr">0, 600</span>

d) <span lang="en">1, 100, 101, 500</span><br><span lang="tr">1, 100, 101, 500</span>

Bir seçenek seçin.


### S21–S30



**Soru 21** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>During a review, one participant keeps the discussion on time, ensures that quieter people can contribute, and records the newly agreed actions. Which assessment of this assignment is correct?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir gözden geçirmede katılımcılardan biri tartışmanın süresini gözetir, daha sessiz kişilerin katkıda bulunabilmesini sağlar ve yeni kararlaştırılan eylemleri kaydeder. Bu görevlendirmeyle ilgili hangi değerlendirme doğrudur?

</div>

a) <span lang="en">The participant is the author because moderating discussion and recording actions correct the work product</span><br><span lang="tr">Tartışmayı yönetmek ve eylemleri kaydetmek iş ürününü düzelttiğinden bu katılımcı yazardır.</span>

b) <span lang="en">The participant combines moderator and scribe responsibilities; review participants may hold several roles</span><br><span lang="tr">Katılımcı moderatör ve katip sorumluluklarını birleştirir; katılımcılar birden çok rol üstlenebilir.</span>

c) <span lang="en">The participant is the manager because the meeting discussion determines the review budget</span><br><span lang="tr">Toplantıdaki tartışma gözden geçirme bütçesini belirlediğinden bu katılımcı yöneticidir.</span>

d) <span lang="en">The participant combines reviewer and author responsibilities because each meeting action is a content correction</span><br><span lang="tr">Her toplantı eylemi bir içerik düzeltmesi olduğundan katılımcı gözden geçirici ve yazar rollerini birleştirir.</span>

Bir seçenek seçin.



**Soru 22** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>An author plans a walkthrough to teach colleagues about a new interface. A participant objects to logging anomalies because the meeting has an educational goal. Which response fits this review type?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir yazar yeni bir arayüzü çalışma arkadaşlarına öğretmek için üzerinden geçme (walkthrough) planlar. Bir katılımcı, toplantının eğitim amacı bulunduğu için anomalilerin kaydedilmesine itiraz eder. Hangi yanıt bu gözden geçirme türüne uygundur?

</div>

a) <span lang="en">Accept the objection because an educational walkthrough excludes logging anomalies</span><br><span lang="tr">Eğitim amaçlı üzerinden geçme anomalilerin kaydını dışladığından itirazı kabul etmek</span>

b) <span lang="en">Convert the meeting into an inspection because walkthroughs are limited to presentations</span><br><span lang="tr">Üzerinden geçme sunumlarla sınırlı olduğundan toplantıyı teftişe dönüştürmek</span>

c) <span lang="en">Keep the walkthrough: it can support learning and also identify anomalies</span><br><span lang="tr">Üzerinden geçmeyi sürdürmek; hem öğrenmeyi destekleyebilir hem anomalileri bulabilir.</span>

d) <span lang="en">Replace the author with a moderator because walkthroughs require a moderator to lead</span><br><span lang="tr">Üzerinden geçmeyi moderatör yönetmek zorunda olduğundan yazarın yerine moderatör koymak</span>

Bir seçenek seçin.



**Soru 23** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Which statement about regression testing is correct?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Regresyon testiyle ilgili hangi ifade doğrudur?

</div>

a) <span lang="en">Regression test suites run many times and grow over the iterations, which makes them strong candidates for automation</span><br><span lang="tr">Regresyon test takımları çok kez koşulur ve döngüler boyunca büyür; bu nedenle otomasyona güçlü adaydır.</span>

b) <span lang="en">Regression testing is performed to confirm that a specific defect fix has resolved the original problem</span><br><span lang="tr">Regresyon testi, belirli bir hata düzeltmesinin başlangıçtaki problemi çözdüğünü onaylamak için yapılır.</span>

c) <span lang="en">Regression testing targets the changed parts of the system rather than the unchanged ones</span><br><span lang="tr">Regresyon testi, sistemin değişmeyen kısımları yerine değişen kısımlarını hedefler.</span>

d) <span lang="en">Regression testing becomes unnecessary once the development process reaches a high maturity</span><br><span lang="tr">Geliştirme süreci yüksek olgunluğa ulaştığında regresyon testine gerek kalmaz.</span>

Bir seçenek seçin.



**Soru 24** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Testing of a release has ended. The sponsor wants a summary of what differed from the agreed plan, the quality concerns still outstanding, and improvements for the next release. Which response best meets this request?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir sürümün testleri bitmiştir. Sponsor, kararlaştırılan plandan sapmaların, devam eden kalite kaygılarının ve sonraki sürüm için iyileştirmelerin özetini ister. Hangi yanıt bu isteği **EN İYİ** karşılar?

</div>

a) <span lang="en">Send the next week's planned testing and leave out the completed release's evaluation</span><br><span lang="tr">Sonraki haftanın planlanan testlerini gönderip biten sürümün değerlendirmesini dışarıda bırakmak</span>

b) <span lang="en">Send the daily change in newly reported defects without a release-level assessment</span><br><span lang="tr">Sürüm düzeyinde değerlendirme yapmadan yeni bildirilen hatalardaki günlük değişimi göndermek</span>

c) <span lang="en">Prepare a completion report covering deviations, unmitigated risks and lessons learned</span><br><span lang="tr">Sapmaları, azaltılmamış riskleri ve çıkarılan dersleri içeren tamamlama raporu hazırlamak</span>

d) <span lang="en">Prepare a new execution schedule and treat it as evidence that the release is complete</span><br><span lang="tr">Yeni koşum takvimi hazırlayıp bunu sürümün tamamlandığına ilişkin kanıt saymak</span>

Bir seçenek seçin.



**Soru 25** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>The team uses coverage-based prioritization: rank each test by the total number of requirements it covers, with the largest total first. Coverage already provided by an earlier test does not reduce a later test's ranking. All four tests are executable and have equal duration.</p>
<div class="table-wrap"><table>
<thead>
<tr>
<th>Test</th>
<th>Requirements covered</th>
</tr>
</thead>
<tbody>
<tr>
<td>TC-L</td>
<td>R1, R2, R3, R4, R5</td>
</tr>
<tr>
<td>TC-M</td>
<td>R1, R2, R3, R4</td>
</tr>
<tr>
<td>TC-N</td>
<td>R4, R5, R6</td>
</tr>
<tr>
<td>TC-P</td>
<td>R5, R6</td>
</tr>
</tbody>
</table></div>
<p>Which execution order follows this rule?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Ekip kapsama dayalı önceliklendirme kullanır: her testi kapsadığı **toplam** gereksinim sayısına göre, en yüksek toplam önce gelecek biçimde sıralar. Önceki bir testin sağladığı kapsam, sonraki testin sırasını düşürmez. Dört testin hepsi koşulabilir ve süreleri eşittir.

| Test | Kapsanan gereksinimler |
|---|---|
| TC-L | R1, R2, R3, R4, R5 |
| TC-M | R1, R2, R3, R4 |
| TC-N | R4, R5, R6 |
| TC-P | R5, R6 |

Hangi koşum sırası bu kurala uyar?

</div>

a) <span lang="en">TC-L, TC-M, TC-N, TC-P</span><br><span lang="tr">TC-L, TC-M, TC-N, TC-P</span>

b) <span lang="en">TC-L, TC-N, TC-M, TC-P</span><br><span lang="tr">TC-L, TC-N, TC-M, TC-P</span>

c) <span lang="en">TC-N, TC-L, TC-M, TC-P</span><br><span lang="tr">TC-N, TC-L, TC-M, TC-P</span>

d) <span lang="en">TC-P, TC-N, TC-M, TC-L</span><br><span lang="tr">TC-P, TC-N, TC-M, TC-L</span>

Bir seçenek seçin.



**Soru 26** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A retrospective identifies slow feedback from a shared test environment. The team tries reserved access slots in the next iteration and compares the waiting time with the earlier results. Why is this useful for testing?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Geçmişe dönük öğeler çalışmasında, ortak test ortamının geri bildirimi geciktirdiği belirlenir. Ekip sonraki döngüde ayrılmış erişim zamanları dener ve bekleme süresini önceki sonuçlarla karşılaştırır. Bunun test açısından yararı nedir?

</div>

a) <span lang="en">It transfers responsibility for testing from the team to the environment administrator</span><br><span lang="tr">Test sorumluluğunu ekipten ortam yöneticisine devreder.</span>

b) <span lang="en">It makes the retrospective result an exit criterion for the current test level</span><br><span lang="tr">Geçmişe dönük çalışmanın sonucunu mevcut test seviyesinin çıkış kriteri yapar.</span>

c) <span lang="en">It demonstrates that later iterations can omit test monitoring once the slots are assigned</span><br><span lang="tr">Zamanlar ayrılınca sonraki döngülerde test gözetiminin atlanabileceğini gösterir.</span>

d) <span lang="en">It turns reflection into an evaluated process change that can improve testing efficiency</span><br><span lang="tr">Değerlendirmeyi, etkisi ölçülen ve test verimliliğini artırabilecek değişime çevirmek</span>

Bir seçenek seçin.



**Soru 27** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A team has extensive white-box coverage of its implementation, but a required export function is absent. A manager says the coverage result proves that every required function exists. How should the tester respond?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir ekip uygulamasında yüksek beyaz kutu kapsamı sağlamıştır; ancak gerekli bir dışa aktarma fonksiyonu eksiktir. Yönetici, kapsam sonucunun gerekli her fonksiyonun bulunduğunu kanıtladığını söyler. Test uzmanı nasıl yanıt vermelidir?

</div>

a) <span lang="en">Coverage of implemented structure may miss omitted functionality, so compare the product with its requirements</span><br><span lang="tr">Uygulanmış yapının kapsamı eksik fonksiyonları gözden kaçırabilir; ürünü gereksinimlerle karşılaştırın.</span>

b) <span lang="en">Coverage of implemented structure proves completeness, so close the missing-function report</span><br><span lang="tr">Uygulanmış yapının kapsamı eksiksizliği kanıtlar; eksik fonksiyon raporunu kapatın.</span>

c) <span lang="en">Coverage of implemented structure is subjective, so discard the coverage measurements</span><br><span lang="tr">Uygulanmış yapının kapsamı özneldir; kapsam ölçümlerini değerlendirme dışı bırakın.</span>

d) <span lang="en">Coverage of implemented structure requires complete requirements, so the export function must already exist</span><br><span lang="tr">Uygulanmış yapının kapsamı eksiksiz gereksinimler ister; dolayısıyla dışa aktarma zaten bulunmalıdır.</span>

Bir seçenek seçin.



**Soru 28** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A release risk log contains the following entries. Which entry describes a PRODUCT risk?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir sürümün risk kaydında aşağıdaki maddeler bulunur. Hangisi bir **ÜRÜN** riskini anlatır?

</div>

a) <span lang="en">Screen-reader users may be unable to identify and activate the checkout controls</span><br><span lang="tr">Ekran okuyucu kullanıcıları ödeme kontrollerini tanıyıp etkinleştiremeyebilir.</span>

b) <span lang="en">Two experienced testers may leave the project in the middle of system testing</span><br><span lang="tr">İki deneyimli test uzmanı sistem testinin ortasında projeden ayrılabilir.</span>

c) <span lang="en">The middleware supplier may deliver the licensed components late</span><br><span lang="tr">Ara katman tedarikçisi lisanslı bileşenleri geç teslim edebilir.</span>

d) <span lang="en">Scope creep may enlarge the backlog beyond the planned budget</span><br><span lang="tr">Kapsam kayması iş listesini planlanan bütçenin ötesine büyütebilir.</span>

Bir seçenek seçin.



**Soru 29** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A tester is preparing a defect report for a notification service. The requirement is: "A repeated request with the same request ID must return the original notification ID and must not create another notification." The environment is service v3.8, build 614, with an empty notification store. The tester recorded:</p>
<div class="table-wrap"><table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr>
<th>Step</th>
<th>Request</th>
<th>Response</th>
<th>Store afterwards</th>
</tr>
</thead>
<tbody>
<tr>
<td>1</td>
<td>Send request ID R-84, recipient user-7</td>
<td>Notification N-901</td>
<td>N-901</td>
</tr>
<tr>
<td>2</td>
<td>Repeat the same request unchanged</td>
<td>Notification N-902</td>
<td>N-901 and N-902</td>
</tr>
</tbody>
</table></div>
<p>Which report excerpt correctly states the reproduction and expected/actual results?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir test uzmanı bildirim servisi için hata raporu hazırlamaktadır. Gereksinim şöyledir: “Aynı istek kimliğiyle yinelenen istek ilk bildirim kimliğini döndürmeli ve başka bildirim oluşturmamalıdır.” Ortam servis v3.8, yapı (build) 614 ve boş bildirim deposudur. Şu kayıtlar alınmıştır:

| Adım | İstek | Yanıt | Sonrasında depo |
|---|---|---|---|
| 1 | R-84 istek kimliğini, user-7 alıcısıyla gönder | Bildirim N-901 | N-901 |
| 2 | Aynı isteği değiştirmeden yinele | Bildirim N-902 | N-901 ve N-902 |

Hangi rapor alıntısı yeniden üretim adımlarını, beklenen ve gerçekleşen sonuçları doğru belirtir?

</div>

a) <span lang="en">Send two requests with different IDs; expect one notification; actual result is N-901 and N-902</span><br><span lang="tr">Farklı kimlikli iki istek gönder; tek bildirim bekle; gerçekleşen sonuç N-901 ve N-902’dir.</span>

b) <span lang="en">Send R-84 once; expect N-901; actual result is N-901, so the first send fails</span><br><span lang="tr">R-84’ü bir kez gönder; N-901 bekle; gerçekleşen sonuç N-901 olduğundan ilk gönderim başarısızdır.</span>

c) <span lang="en">Repeat R-84 unchanged; expect N-902 to be created; actual result is N-901, so retry fails</span><br><span lang="tr">R-84’ü değiştirmeden yinele; N-902 oluşmasını bekle; gerçekleşen sonuç N-901 olduğundan yineleme başarısızdır.</span>

d) <span lang="en">Send R-84, then repeat it unchanged; expect N-901 again and one stored notification; actual is N-902 and two</span><br><span lang="tr">R-84’ü gönder, değiştirmeden yinele; yeniden N-901 ve depoda tek bildirim bekle; gerçekleşen N-902 ve iki kayıttır.</span>

Bir seçenek seçin.



**Soru 30** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A tester derives tests from input partitions, then uses experience with earlier mobile applications to add interruption and duplicate-submission tests. How should the second activity relate to the partition tests?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir test uzmanı girdi paylarından testler türetir. Ardından önceki mobil uygulama deneyimiyle kesinti ve yinelenen gönderim testleri ekler. İkinci aktivitenin pay testleriyle ilişkisi nasıl olmalıdır?

</div>

a) <span lang="en">It establishes complete statement coverage without examining any implementation structure</span><br><span lang="tr">Uygulamanın yapısını incelemeden tam komut kapsamı sağlar.</span>

b) <span lang="en">It supersedes the partition tests because past failures provide a complete test basis</span><br><span lang="tr">Geçmiş arızalar eksiksiz test esası sağladığından pay testlerinin yerini alır.</span>

c) <span lang="en">It complements the partition tests and may expose defects those tests do not detect</span><br><span lang="tr">Pay testlerini tamamlar ve onların tespit etmediği hataları ortaya çıkarabilir.</span>

d) <span lang="en">It converts the partition tests into white-box tests because it uses technical experience</span><br><span lang="tr">Teknik tecrübe kullandığından pay testlerini beyaz kutu testlerine dönüştürür.</span>

Bir seçenek seçin.


### S31–S40



**Soru 31** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>To test a fee calculation, a tester reads the requirements document, splits the input ranges into partitions and selects representative values from each. The tester never looks at the code and does not draw on personal hunches. Which category of test techniques is being applied?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir test uzmanı ücret hesabını sınamak için gereksinim belgesini okur, girdi aralıklarını denklik paylarına ayırır ve her paydan temsilci değerler seçer. Koda bakmaz ve kişisel sezgilerinden yararlanmaz. Hangi test tekniği kategorisini uygular?

</div>

a) <span lang="en">Experience-based test techniques</span><br><span lang="tr">Tecrübeye dayalı test teknikleri</span>

b) <span lang="en">Black-box test techniques</span><br><span lang="tr">Kara kutu test teknikleri</span>

c) <span lang="en">White-box test techniques</span><br><span lang="tr">Beyaz kutu test teknikleri</span>

d) <span lang="en">Non-functional test types</span><br><span lang="tr">Fonksiyonel olmayan test çeşitleri</span>

Bir seçenek seçin.



**Soru 32** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Working under heavy deadline pressure and without training in the new framework, a developer writes an incorrect API call in the payment module. Weeks later, customer payments start to crash. What is the ROOT CAUSE in this scenario?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Yoğun teslim tarihi baskısı altında çalışan ve yeni yazılım çatısı konusunda eğitim almamış bir geliştirici, ödeme modülüne yanlış bir API çağrısı yazar. Haftalar sonra müşterilerin ödeme işlemleri çökmeye başlar. Bu senaryodaki **KÖK NEDEN** nedir?

</div>

a) <span lang="en">The incorrect API call in the payment module</span><br><span lang="tr">Ödeme modülündeki yanlış API çağrısı</span>

b) <span lang="en">The haste and inexperience that caused the mistake</span><br><span lang="tr">İnsan hatasına yol açan acele ve deneyimsizlik</span>

c) <span lang="en">The crash that the paying customers experienced</span><br><span lang="tr">Ödeme yapan müşterilerin yaşadığı çökme</span>

d) <span lang="en">The absence of an automated regression test for the payment module</span><br><span lang="tr">Ödeme modülü için otomatik regresyon testinin bulunmaması</span>

Bir seçenek seçin.



**Soru 33** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A team has budgeted for earlier test activities, but the business stakeholders still consider testing a final handover and decline to support the change. Which condition for adopting shift left needs attention?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir ekip erken test aktiviteleri için bütçe ayırmıştır. Ancak iş paydaşları testi hâlâ son teslim aşaması olarak görür ve değişikliği desteklemez. Sola alma (shift left) yaklaşımını benimsemek için hangi koşula dikkat edilmelidir?

</div>

a) <span lang="en">Convince stakeholders of the approach and obtain their support for earlier testing</span><br><span lang="tr">Paydaşları yaklaşıma ikna etmek ve erken test için desteklerini almak</span>

b) <span lang="en">Move the early activities back to final handover and call the result shift left</span><br><span lang="tr">Erken aktiviteleri son teslim aşamasına geri taşıyıp sonucu sola alma diye adlandırmak</span>

c) <span lang="en">Remove the need for stakeholders to support earlier testing by increasing the automation budget</span><br><span lang="tr">Otomasyon bütçesini artırarak erken test için paydaş desteği gereksinimini kaldırmak</span>

d) <span lang="en">Delay discussion of the approach until system testing has already been completed</span><br><span lang="tr">Yaklaşımın görüşülmesini sistem testi tamamlanana kadar ertelemek</span>

Bir seçenek seçin.



**Soru 34** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Static analysis flags unreachable code and a requirement review finds an ambiguous response-time limit. The team then runs concurrent requests and observes unacceptable response times. Which comparison is accurate?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Statik analiz erişilemeyen kodu işaretler; bir gereksinim gözden geçirmesi belirsiz bir yanıt süresi sınırı bulur. Ekip daha sonra eşzamanlı istekler koşar ve kabul edilemez yanıt süreleri gözlemler. Hangi karşılaştırma doğrudur?

</div>

a) <span lang="en">Static testing detects issues in work products directly; dynamic testing observes failures during execution</span><br><span lang="tr">Statik test iş ürünlerindeki sorunları doğrudan tespit eder; dinamik test koşum sırasında arızaları gözlemler.</span>

b) <span lang="en">Static testing observes failures during execution; dynamic testing detects issues in work products directly</span><br><span lang="tr">Statik test koşum sırasında arızaları gözlemler; dinamik test iş ürünlerindeki sorunları doğrudan tespit eder.</span>

c) <span lang="en">Static testing and dynamic testing provide the same evidence because each reported item concerns a defect</span><br><span lang="tr">Bildirilen her öğe bir hatayla ilgili olduğundan statik ve dinamik test aynı kanıtı sağlar.</span>

d) <span lang="en">Static testing measures actual response times; dynamic testing determines whether the requirement is ambiguous</span><br><span lang="tr">Statik test gerçekleşen yanıt sürelerini ölçer; dinamik test gereksinimin belirsiz olup olmadığını belirler.</span>

Bir seçenek seçin.



**Soru 35** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A tester counts the two outcomes of every conditional decision but leaves unconditional transfers out of the coverage inventory. The tester calls the result branch coverage. What correction is needed?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir test uzmanı her koşullu kararın iki sonucunu sayar, ancak koşulsuz aktarımları kapsam envanterinin dışında bırakır. Sonucu dal kapsamı olarak adlandırır. Hangi düzeltme gerekir?

</div>

a) <span lang="en">Use the requirements as coverage items instead of any transfers in the code</span><br><span lang="tr">Koddaki aktarımlar yerine gereksinimleri kapsam öğeleri olarak kullanmak</span>

b) <span lang="en">Use executable statements as the coverage items and keep the branch label</span><br><span lang="tr">Kapsam öğesi olarak çalıştırılabilir komutları kullanıp dal adını korumak</span>

c) <span lang="en">Exclude unconditional transfers because conditional outcomes define the complete branch inventory</span><br><span lang="tr">Koşullu sonuçlar bütün dal envanterini tanımladığından koşulsuz aktarımları dışlamak</span>

d) <span lang="en">Include unconditional and conditional branches in the branch coverage inventory</span><br><span lang="tr">Dal kapsamı envanterine hem koşulsuz hem koşullu dalları dahil etmek</span>

Bir seçenek seçin.



**Soru 36** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Before the official launch, a pre-release version of a banking app is made available to a selected group of external customers, who use it at their own locations and report their experiences. Which form of testing is this?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir bankacılık uygulamasının yayım öncesi sürümü, resmî çıkıştan önce seçilmiş dış müşterilere sunulur. Müşteriler uygulamayı kendi yerlerinde kullanır ve deneyimlerini bildirir. Bu hangi test biçimidir?

</div>

a) <span lang="en">Alpha testing</span><br><span lang="tr">Alfa testi</span>

b) <span lang="en">Beta testing</span><br><span lang="tr">Beta testi</span>

c) <span lang="en">Operational acceptance testing</span><br><span lang="tr">Operasyonel kabul testi</span>

d) <span lang="en">System testing</span><br><span lang="tr">Sistem testi</span>

Bir seçenek seçin.



**Soru 37** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A team uses a rule-oriented acceptance-criteria list for a discount story. A reviewer claims that the list cannot communicate the story's scope because it is not written as Given/When/Then scenarios. Which assessment is appropriate?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir ekip indirimle ilgili kullanıcı hikayesi için kural odaklı kabul kriterleri listesi kullanır. Bir gözden geçirici, liste Given/When/Then senaryolarıyla yazılmadığından hikayenin kapsamını aktaramayacağını söyler. Hangi değerlendirme uygundur?

</div>

a) <span lang="en">The claim is valid because a rule-oriented list is a test procedure rather than acceptance criteria</span><br><span lang="tr">İddia geçerlidir; kural odaklı liste kabul kriterleri değil, test prosedürüdür.</span>

b) <span lang="en">The claim is valid because checklist-based testing is the required acceptance-criteria format</span><br><span lang="tr">İddia geçerlidir; zorunlu kabul kriteri biçimi kontrol listesine dayalı testtir.</span>

c) <span lang="en">The claim is invalid because acceptance criteria must describe implementation structure</span><br><span lang="tr">İddia geçersizdir; kabul kriterleri uygulamanın iç yapısını anlatmak zorundadır.</span>

d) <span lang="en">The claim is invalid because rule-oriented criteria can also state the acceptance conditions</span><br><span lang="tr">İddia geçersizdir; kural odaklı kriterler de kabul koşullarını belirtebilir.</span>

Bir seçenek seçin.



**Soru 38** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A pipeline tool builds the application after each merge, deploys it to a fresh test environment, triggers the automated suites in sequence and promotes the build when they pass. Its primary purpose is to orchestrate the delivery pipeline rather than implement the individual tests. Which tool category best matches that purpose?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir teslimat hattı aracı her birleştirmeden sonra uygulamayı derler, yeni test ortamına kurar, otomatik test takımlarını sırayla tetikler ve testler geçtiğinde yapıyı sonraki aşamaya geçirir. Temel amacı tek tek testleri oluşturmak değil, teslimat hattını düzenlemektir. Hangi araç kategorisi bu amaca **EN İYİ** uyar?

</div>

a) <span lang="en">A tool for test design and test implementation in the delivery process</span><br><span lang="tr">Teslimat sürecinde test tasarımı ve test uyarlama aracı</span>

b) <span lang="en">A static testing tool for analyzing the source code</span><br><span lang="tr">Kaynak kodunu analiz eden statik test aracı</span>

c) <span lang="en">A DevOps tool supporting continuous integration and delivery</span><br><span lang="tr">Sürekli entegrasyon ve teslimatı destekleyen DevOps aracı</span>

d) <span lang="en">A tool for managing the test process and its testware</span><br><span lang="tr">Test sürecini ve test çalışma ürünlerini yöneten araç</span>

Bir seçenek seçin.



**Soru 39** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Test design has just finished for the payment feature. Which work products has this activity produced?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Ödeme özelliğinin test tasarımı yeni tamamlanmıştır. Bu aktivite hangi iş ürünlerini üretmiştir?

</div>

a) <span lang="en">Test cases and test data requirements</span><br><span lang="tr">Test senaryoları ve test verisi gereksinimleri</span>

b) <span lang="en">Test procedures and automated test scripts</span><br><span lang="tr">Test prosedürleri ve otomatik test betikleri</span>

c) <span lang="en">Test conditions and the prioritized test basis</span><br><span lang="tr">Test koşulları ve önceliklendirilmiş test esası</span>

d) <span lang="en">Test logs and test progress reports</span><br><span lang="tr">Test kayıtları ve test ilerleme raporları</span>

Bir seçenek seçin.



**Soru 40** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A developer exhaustively tests a tiny function with two Boolean inputs by checking all four input combinations. A manager says this disproves the principle that exhaustive testing is impossible. Which assessment is correct?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir geliştirici, iki Boole girdili çok küçük bir fonksiyonun dört girdi birleşiminin tamamını kontrol ederek kapsamlı test yapar. Bir yönetici bunun “Yazılımı %100 test etmek imkansızdır” ilkesini çürüttüğünü söyler. Hangi değerlendirme doğrudur?

</div>

a) <span lang="en">The principle is disproved because a finite input space makes exhaustive testing practical for any product</span><br><span lang="tr">Sonlu girdi uzayı her ürünün tümüyle test edilmesini uygulanabilir kıldığı için ilke çürütülmüştür.</span>

b) <span lang="en">The manager is correct because exhaustive input testing proves the entire product is defect-free</span><br><span lang="tr">Girdilerin tümünü test etmek bütün ürünün hatasızlığını kanıtladığı için yönetici haklıdır.</span>

c) <span lang="en">The example is compatible with the principle, which allows exhaustive testing in trivial cases</span><br><span lang="tr">Örnek, çok basit durumlarda tüm olasılıkların testine izin veren ilkeyle uyumludur.</span>

d) <span lang="en">The example is invalid because exhaustive testing must include production traffic</span><br><span lang="tr">Tüm olasılıkların testi üretim trafiğini de içermek zorunda olduğundan örnek geçersizdir.</span>

Bir seçenek seçin.


## Part 2 — Cevap anahtarı ve skor değerlendirmesi

### Cevap anahtarı

| Soru | Cevap | Bölüm | LO | K |
|---|---|---|---|---|
| 1 | c | 4 | FL-4.2.3 | K3 |
| 2 | d | 1 | FL-1.4.1 | K2 |
| 3 | b, e | 6 | FL-6.2.1 | K1 |
| 4 | b | 4 | FL-4.2.4 | K3 |
| 5 | b | 5 | FL-5.4.1 | K2 |
| 6 | d | 3 | FL-3.2.5 | K1 |
| 7 | a | 5 | FL-5.1.2 | K1 |
| 8 | a | 2 | FL-2.1.3 | K1 |
| 9 | b | 5 | FL-5.1.4 | K3 |
| 10 | d | 5 | FL-5.1.7 | K2 |
| 11 | b | 5 | FL-5.1.3 | K2 |
| 12 | c | 4 | FL-4.2.2 | K3 |
| 13 | b | 1 | FL-1.4.5 | K2 |
| 14 | d | 4 | FL-4.5.3 | K3 |
| 15 | d | 1 | FL-1.5.3 | K2 |
| 16 | b | 4 | FL-4.4.2 | K2 |
| 17 | a | 1 | FL-1.2.2 | K1 |
| 18 | d | 1 | FL-1.5.2 | K1 |
| 19 | c | 2 | FL-2.1.2 | K1 |
| 20 | a | 4 | FL-4.2.1 | K3 |
| 21 | b | 3 | FL-3.2.3 | K1 |
| 22 | c | 3 | FL-3.2.4 | K2 |
| 23 | a | 2 | FL-2.2.3 | K2 |
| 24 | c | 5 | FL-5.3.2 | K2 |
| 25 | a | 5 | FL-5.1.5 | K3 |
| 26 | d | 2 | FL-2.1.6 | K2 |
| 27 | a | 4 | FL-4.3.3 | K2 |
| 28 | a | 5 | FL-5.2.2 | K2 |
| 29 | d | 5 | FL-5.5.1 | K3 |
| 30 | c | 4 | FL-4.4.1 | K2 |
| 31 | b | 4 | FL-4.1.1 | K2 |
| 32 | b | 1 | FL-1.2.3 | K2 |
| 33 | a | 2 | FL-2.1.5 | K2 |
| 34 | a | 3 | FL-3.1.3 | K2 |
| 35 | d | 4 | FL-4.3.2 | K2 |
| 36 | b | 2 | FL-2.2.1 | K2 |
| 37 | d | 4 | FL-4.5.2 | K2 |
| 38 | c | 6 | FL-6.1.1 | K2 |
| 39 | a | 1 | FL-1.4.3 | K2 |
| 40 | c | 1 | FL-1.3.1 | K2 |

### Skor bantları

- **35–40:** Bu denemede güçlü bir sonuç aldınız; başka bir süreli denemeyle doğrulayın.
- **30–34:** Bu denemede geçme çizgisinin üzerindesiniz; yanlışlarınızı gözden geçirin.
- **26–29:** Geçer; zayıf bölümlerinizi güçlendirin.
- **0–25:** Bu denemede geçme çizgisinin altındasınız; bölüm skor kartına göre çalışma rotası belirleyin.

Bu bantlar ilk, cevaplara bakılmadan yapılan süreli deneme için çalışma önerisidir; tekrar çözüm aynı ölçüm değildir; tek bir deneme sonucu gerçek sınav başarısını garanti etmez. Çalışma modunda açıklamaları görerek alınan puanı süreli prova puanıyla karşılaştırmayın.

### Bölüm skor kartı

Hedef, her bölümde en az %65 için gereken doğru sayısıdır; kesirli sonuç yukarı yuvarlanır. Bu bölüm hedefleri resmî bölüm bazında geçme barajı değildir. Resmî geçme ölçütü toplam 26/40'tır.

| Bölüm | Soru sayısı | Doğru sayınız | Hedef (%65) | Çalışma önerisi |
|---|---:|---|---|---|
| 1 — Temeller | 8 | | 6/8 | Hedefleri, aktiviteleri ve temel kavram ayrımlarını tekrar edin. |
| 2 — Yaşam döngüsü | 6 | | 4/6 | Test seviyelerini, önce test ve sola alma yaklaşımlarını karşılaştırın. |
| 3 — Statik test | 4 | | 3/4 | Statik/dinamik ayrımı, roller ve gözden geçirme türlerini çalışın. |
| 4 — Analiz ve tasarım | 11 | | 8/11 | Teknikleri veri üzerinde uygulayın, yanlış varyantları karşılaştırın. |
| 5 — Yönetim | 9 | | 6/9 | Planlama, tahmin, önceliklendirme, raporlama ve hata yönetimini çalışın. |
| 6 — Araçlar | 2 | | 2/2 | Araç işlevlerini ve otomasyon risklerini tekrar edin. |


## Part 3 — Açıklamalar

### S1–S10



**Soru 1** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>An alert service uses the full decision table below. T and F mean true and false. The team wants to merge R1 and R2 into one rule without changing the behavior.</p>
<div class="table-wrap"><table style="width:100%;">
<colgroup>
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<thead>
<tr>
<th>Condition / action</th>
<th>R1</th>
<th>R2</th>
<th>R3</th>
<th>R4</th>
<th>R5</th>
<th>R6</th>
<th>R7</th>
<th>R8</th>
</tr>
</thead>
<tbody>
<tr>
<td>Account active</td>
<td>T</td>
<td>T</td>
<td>T</td>
<td>T</td>
<td>F</td>
<td>F</td>
<td>F</td>
<td>F</td>
</tr>
<tr>
<td>Alert urgent</td>
<td>T</td>
<td>T</td>
<td>F</td>
<td>F</td>
<td>T</td>
<td>T</td>
<td>F</td>
<td>F</td>
</tr>
<tr>
<td>Subscribed</td>
<td>T</td>
<td>F</td>
<td>T</td>
<td>F</td>
<td>T</td>
<td>F</td>
<td>T</td>
<td>F</td>
</tr>
<tr>
<td>Result</td>
<td>Send</td>
<td>Send</td>
<td>Send</td>
<td>Suppress</td>
<td>Suppress</td>
<td>Suppress</td>
<td>Suppress</td>
<td>Suppress</td>
</tr>
</tbody>
</table></div>
<p>Which merged rule replaces exactly R1 and R2? A dash means that either value is accepted.</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir uyarı servisi aşağıdaki tam karar tablosunu kullanır. D ve Y, doğru ve yanlış anlamındadır. Ekip davranışı değiştirmeden R1 ve R2'yi tek kuralda birleştirmek ister.

| Koşul / eylem | R1 | R2 | R3 | R4 | R5 | R6 | R7 | R8 |
|---|---|---|---|---|---|---|---|---|
| Hesap aktif | D | D | D | D | Y | Y | Y | Y |
| Uyarı acil | D | D | Y | Y | D | D | Y | Y |
| Abone | D | Y | D | Y | D | Y | D | Y |
| Sonuç | Gönder | Gönder | Gönder | Gönderme | Gönderme | Gönderme | Gönderme | Gönderme |

Hangi birleşik kural tam olarak R1 ve R2'nin yerini alır? Çizgi (–), iki değerin de kabul edildiğini gösterir.

</div>

a) <span lang="en">Active = T, urgent = –, subscribed = T; result = Send</span><br><span lang="tr">Aktif = D, acil = –, abone = D; sonuç = Gönder</span>

b) <span lang="en">Active = –, urgent = T, subscribed = –; result = Send</span><br><span lang="tr">Aktif = –, acil = D, abone = –; sonuç = Gönder</span>

c) <span lang="en">Active = T, urgent = T, subscribed = –; result = Send</span><br><span lang="tr">Aktif = D, acil = D, abone = –; sonuç = Gönder</span>

d) <span lang="en">Active = T, urgent = –, subscribed = –; result = Send</span><br><span lang="tr">Aktif = D, acil = –, abone = –; sonuç = Gönder</span>

Bir seçenek seçin.

**Soru 1 — Doğru cevap: c**

**Neden doğru:** Adım adım: 1. R1 ve R2 için aktif = D, acil = D ve sonuç = Gönder değerlerini karşılaştırın; aynıdır. 2. Abone koşulunun birinde D, diğerinde Y olduğunu görün. 3. Bu koşulu – ile değiştirin ve diğerlerini koruyun. Birleşik kural açıldığında tam olarak başlangıçtaki iki birleşimi üretir.

**En cazip yanlış (near-miss) — d:** Daha çok koşulu kaldırmak tabloyu daha fazla sadeleştiriyor gibi görünebilir. Ancak acil koşulunu da kaldırmak R4 durumunu kapsar. R4 sonucu Gönderme olduğundan davranış değişir.

**Diğer şıklar:** a) Bu kural R1 ve R3 birleşimlerini kapsar. İstenen R1 ve R2 çiftini temsil etmez. · b) Aktif koşulunu kaldırarak R5 ve R6 gibi aktif olmayan hesapları da kapsar. Bunların sonucu Gönderme olduğundan kural geçersizdir.

*Kaçırdıysanız tekrar edin: Kara kutu test teknikleri | Tuzak: Prosedür hatası | LO: FL-4.2.3 (K3)*

[Kılavuzda tekrar edin: Kara kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-2-3)



**Soru 2** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Every week, the test lead compares the actual test progress against the test plan, and when execution falls behind, re-prioritizes the remaining tests and requests an additional tester. Which test activity is the test lead performing?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Test lideri her hafta gerçekleşen test ilerlemesini test planıyla karşılaştırır. Test koşumu geride kaldığında kalan testleri yeniden önceliklendirir ve ek bir test uzmanı talep eder. Test lideri hangi test aktivitesini yürütmektedir?

</div>

a) <span lang="en">The test planning activity</span><br><span lang="tr">Test planlama aktivitesi</span>

b) <span lang="en">The test analysis activity</span><br><span lang="tr">Test analizi aktivitesi</span>

c) <span lang="en">The test implementation activity</span><br><span lang="tr">Test uyarlama aktivitesi</span>

d) <span lang="en">Test monitoring and control</span><br><span lang="tr">Test gözetimi ve kontrolü</span>

Bir seçenek seçin.

**Soru 2 — Doğru cevap: d**

**Neden doğru:** Test gözetimi gerçekleşen ilerlemeyi planla karşılaştırır. Test kontrolü ise sapmalara karşı düzeltici eylemler uygular. Kalan testleri yeniden önceliklendirmek ve ek kaynak istemek, burada ilerleme değerlendirmesine verilen yanıtlardır.

**En cazip yanlış (near-miss) — a:** Öncelik ve personel kararları planlamaya benzediği için caziptir. Ancak kök, mevcut plana göre süren çalışmanın izlenmesini ve sapmaların düzeltilmesini birlikte anlatır; bu ayrım gözetim ve kontrolü işaret eder.

**Diğer şıklar:** b) Test analizi test esasından test koşulları türetir. Kökte test esası üzerinde böyle bir çalışma anlatılmamıştır. · c) Test uyarlama, koşumdan önce test çalışma ürünlerini hazırlar. Kökteki ilerleme karşılaştırması ve yönlendirme bu hazırlık değildir.

*Kaçırdıysanız tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller | Tuzak: Near-miss karışıklığı | LO: FL-1.4.1 (K2)*

[Kılavuzda tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-4-1)



**Soru 3** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A team is assessing risks before automating tests. Which TWO proposals expose the team to automation risks? Select the two risks described by the proposals.</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir ekip test otomasyonuna geçmeden önce riskleri değerlendirir. Hangi **İKİ** öneri ekibi otomasyon riskleriyle karşı karşıya bırakır? Önerilerin anlattığı iki riski seçin.

</div>

a) <span lang="en">Measure coverage to identify behavior that needs additional tests and human assessment</span><br><span lang="tr">Ek test ve insan değerlendirmesi gerektiren davranışları belirlemek için kapsamı ölçmek</span>

b) <span lang="en">Cancel exploratory testing because a passing automated suite is treated as complete assurance</span><br><span lang="tr">Geçen otomatik test takımı tam güvence sayıldığı için keşif testini iptal etmek</span>

c) <span lang="en">Review the effort required to maintain the automated scripts when the application changes</span><br><span lang="tr">Uygulama değiştiğinde otomatik betiklerin bakımı için gereken eforu değerlendirmek</span>

d) <span lang="en">Compare failures with logs before deciding whether the product or a test script is faulty</span><br><span lang="tr">Ürünün mü, betiğin mi hatalı olduğuna karar vermeden arızaları kayıtlarla karşılaştırmak</span>

e) <span lang="en">Commit to a framework without checking its compatibility with the target platforms</span><br><span lang="tr">Hedef platformlarla uyumluluğunu kontrol etmeden bir yazılım çatısına bağlanmak</span>

**İKİ seçenek seçin.**

**Soru 3 — Doğru cevap: b, e**

**Neden doğru:** b ve e doğrudur. Geçen otomatik testleri ürün hakkında tam güvence kabul etmek otomasyona aşırı güven oluşturabilir. Hedef platform uyumluluğunu kontrol etmeden çatı seçmek ise uygun olmayan araç riskini getirir. Her iki öneri risk doğuran bir karardır. İki seçeneğin de işaretlenmesi gerekir; bu soruda kısmi puan yoktur.

**En cazip yanlış (near-miss) — a:** Kapsam ölçümü ürüne duyulan güveni etkileyebildiği için risk gibi görünebilir. Ancak burada ölçüm, eksik test ve insan değerlendirmesi ihtiyacını belirlemek için kullanılır; bu otomasyon bilgisinin yapıcı kullanımıdır.

**Diğer şıklar:** c) Bakım eforunu değerlendirmek, bakım yükünü göz ardı etme riskini ele alır. Tarif edilen öneri bu riski doğurmaz. · d) Arızaları inceleyip ürünle test betiğini ayırmak sonuçların bilinçli yorumlanmasını destekler; kör güveni artırmaz.

*Kaçırdıysanız tekrar edin: Test otomasyonunun faydaları ve riskleri | Tuzak: Near-miss karışıklığı | LO: FL-6.2.1 (K1)*

[Kılavuzda tekrar edin: Test otomasyonunun faydaları ve riskleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-6.html#fl-6-2-1)



**Soru 4** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A document workflow starts in Draft. Its complete transitions are: Draft —submit→ Review; Review —reject→ Draft; Review —approve→ Approved; Approved —archive→ Archived. No other transitions are defined.</p>
<figure>
<img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzNDAiIGhlaWdodD0iNDQwIiB2aWV3Qm94PSIwIDAgMzQwIDQ0MCIgcm9sZT0iaW1nIiBhcmlhLWxhYmVsbGVkYnk9InRpdGxlIGRlc2MiPg0KPHRpdGxlIGlkPSJ0aXRsZSI+RG9jdW1lbnQgd29ya2Zsb3c8L3RpdGxlPjxkZXNjIGlkPSJkZXNjIj5EcmFmdCB0byBSZXZpZXcgb24gc3VibWl0LiBSZXZpZXcgdG8gRHJhZnQgb24gcmVqZWN0LiBSZXZpZXcgdG8gQXBwcm92ZWQgb24gYXBwcm92ZS4gQXBwcm92ZWQgdG8gQXJjaGl2ZWQgb24gYXJjaGl2ZS4gSW5pdGlhbCBzdGF0ZSBEcmFmdC48L2Rlc2M+DQo8ZGVmcz48bWFya2VyIGlkPSJhcnJvdyIgbWFya2VyV2lkdGg9IjgiIG1hcmtlckhlaWdodD0iOCIgcmVmWD0iNyIgcmVmWT0iNCIgb3JpZW50PSJhdXRvIj48cGF0aCBkPSJNMCAwIEw4IDQgTDAgOFoiIGZpbGw9IiMyNTQ5NjIiLz48L21hcmtlcj48L2RlZnM+DQo8cmVjdCB3aWR0aD0iMzQwIiBoZWlnaHQ9IjQ0MCIgcng9IjEyIiBmaWxsPSIjZjRmOGZhIi8+DQo8ZyBmaWxsPSIjZmZmZmZmIiBzdHJva2U9IiMyNTQ5NjIiIHN0cm9rZS13aWR0aD0iMiI+DQo8cmVjdCB4PSIxMDYiIHk9IjQzIiB3aWR0aD0iMTQ1IiBoZWlnaHQ9IjQ4IiByeD0iMTAiLz4NCjxyZWN0IHg9IjEwNiIgeT0iMTQ1IiB3aWR0aD0iMTQ1IiBoZWlnaHQ9IjQ4IiByeD0iMTAiLz4NCjxyZWN0IHg9IjEwNiIgeT0iMjQ3IiB3aWR0aD0iMTQ1IiBoZWlnaHQ9IjQ4IiByeD0iMTAiLz4NCjxyZWN0IHg9IjEwNiIgeT0iMzQ5IiB3aWR0aD0iMTQ1IiBoZWlnaHQ9IjQ4IiByeD0iMTAiLz4NCjwvZz4NCjxnIGZvbnQtZmFtaWx5PSJBcmlhbCwgc2Fucy1zZXJpZiIgZm9udC1zaXplPSIxOSIgZmlsbD0iIzE5Mzk0ZSIgdGV4dC1hbmNob3I9Im1pZGRsZSI+DQo8dGV4dCB4PSIxNzgiIHk9Ijc0Ij5EcmFmdDwvdGV4dD48dGV4dCB4PSIxNzgiIHk9IjE3NiI+UmV2aWV3PC90ZXh0Pjx0ZXh0IHg9IjE3OCIgeT0iMjc4Ij5BcHByb3ZlZDwvdGV4dD48dGV4dCB4PSIxNzgiIHk9IjM4MCI+QXJjaGl2ZWQ8L3RleHQ+DQo8L2c+DQo8ZyBmaWxsPSJub25lIiBzdHJva2U9IiMyNTQ5NjIiIHN0cm9rZS13aWR0aD0iMiIgbWFya2VyLWVuZD0idXJsKCNhcnJvdykiPg0KPHBhdGggZD0iTTE3OCAyM1Y0MCIvPjxwYXRoIGQ9Ik0xNzggOTNWMTQxIi8+PHBhdGggZD0iTTE3OCAxOTVWMjQzIi8+PHBhdGggZD0iTTE3OCAyOTdWMzQ1Ii8+DQo8cGF0aCBkPSJNMTA0IDE2OUg2NFY2N0gxMDEiLz4NCjwvZz48Y2lyY2xlIGN4PSIxNzgiIGN5PSIxNyIgcj0iNiIgZmlsbD0iIzI1NDk2MiIvPg0KPGcgZm9udC1mYW1pbHk9IkFyaWFsLCBzYW5zLXNlcmlmIiBmb250LXNpemU9IjE2IiBmaWxsPSIjMTkzOTRlIj4NCjx0ZXh0IHg9IjE5MiIgeT0iMTIzIj5zdWJtaXQ8L3RleHQ+PHRleHQgeD0iMTkyIiB5PSIyMjUiPmFwcHJvdmU8L3RleHQ+PHRleHQgeD0iMTkyIiB5PSIzMjciPmFyY2hpdmU8L3RleHQ+PHRleHQgeD0iMTUiIHk9IjEyNCI+cmVqZWN0PC90ZXh0Pg0KPC9nPjwvc3ZnPg==" alt="Document workflow: Draft to Review by submit; Review to Draft by reject; Review to Approved by approve; Approved to Archived by archive." />
<figcaption aria-hidden="true">Document workflow: Draft to Review by submit; Review to Draft by reject; Review to Approved by approve; Approved to Archived by archive.</figcaption>
</figure>
<p>After which event sequence is the document in Review?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir belge iş akışı Taslak durumunda başlar. Tanımlanmış bütün geçişler şunlardır: Taslak —gönder→ İnceleme; İnceleme —reddet→ Taslak; İnceleme —onayla→ Onaylandı; Onaylandı —arşivle→ Arşivlendi. Başka geçiş tanımlı değildir.

| Başlangıç durumu | Olay | Sonraki durum |
|---|---|---|
| Taslak | gönder | İnceleme |
| İnceleme | reddet | Taslak |
| İnceleme | onayla | Onaylandı |
| Onaylandı | arşivle | Arşivlendi |

Hangi olay dizisinden sonra belge İnceleme durumundadır?

</div>

a) <span lang="en">submit, approve</span><br><span lang="tr">gönder, onayla</span>

b) <span lang="en">submit, reject, submit</span><br><span lang="tr">gönder, reddet, gönder</span>

c) <span lang="en">submit, reject</span><br><span lang="tr">gönder, reddet</span>

d) <span lang="en">submit, approve, archive</span><br><span lang="tr">gönder, onayla, arşivle</span>

Bir seçenek seçin.

**Soru 4 — Doğru cevap: b**

**Neden doğru:** Adım adım: 1. Taslak durumundan başlayın. 2. Gönder olayıyla İnceleme durumuna geçin. 3. Reddet olayıyla Taslak durumuna dönün. 4. İkinci gönder olayıyla yeniden İnceleme durumuna geçin. Dizinin tamamı istenen son durumda biter; adımların geçerli olması tek başına doğru sonuca ulaşıldığını göstermez.

**En cazip yanlış (near-miss) — c:** Olaylar geçerli ve tanıdık olduğu için caziptir. Ancak reddet olayından sonra belge Taslak durumundadır. İnceleme durumuna dönmek için bir gönder olayı daha gerekir.

**Diğer şıklar:** a) Geçerli bir dizidir, ancak Onaylandı durumunda biter. İstenen İnceleme durumunu geçer. · d) Geçerli bir dizidir, ancak Arşivlendi durumunda biter. İstenen son durum değildir.

*Kaçırdıysanız tekrar edin: Kara kutu test teknikleri | Tuzak: Prosedür hatası | LO: FL-4.2.4 (K3)*

[Kılavuzda tekrar edin: Kara kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-2-4)



**Soru 5** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A test report refers to "the payment specification". Two approved versions of that document coexist, and the report does not say which one supplied the expected results. How should configuration management improve the report?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir test raporu “ödeme şartnamesi”ne atıf yapar. Belgenin iki onaylı sürümü aynı anda kullanımdadır; rapor beklenen sonuçların hangi sürüme dayandığını belirtmez. Yapılandırma yönetimi raporu nasıl iyileştirmelidir?

</div>

a) <span lang="en">Replace the document reference with the number of defects found during the run</span><br><span lang="tr">Belge atfını koşumda bulunan hata sayısıyla değiştirmek</span>

b) <span lang="en">Reference the specific controlled specification version used as the test basis</span><br><span lang="tr">Test esasına kaynak olan kontrollü şartname sürümünü belirtmek</span>

c) <span lang="en">Keep the generic document title and add the date the report was distributed</span><br><span lang="tr">Genel belge başlığını koruyup raporun dağıtıldığı tarihi eklemek</span>

d) <span lang="en">Replace the document reference with the severity of the highest open defect</span><br><span lang="tr">Belge atfını en yüksek açık hatanın önem derecesiyle değiştirmek</span>

Bir seçenek seçin.

**Soru 5 — Doğru cevap: b**

**Neden doğru:** Yapılandırma yönetimi, tanımlanmış belge ve yazılım öğelerine açık atıflar yapılmasını destekler. Beklenen sonuçların hangi şartname sürümünden türetildiği belirlenmelidir. Rapor, gerçekten kullanılan kontrollü sürümün kimliğini vermelidir.

**En cazip yanlış (near-miss) — c:** Tarih eklemek belgeyi belirginleştiriyor gibi görünebilir. Ancak dağıtım tarihi bir iletişim olayını tanımlar; iki onaylı sürüm varken hangisinin beklenen sonuçları sağladığını göstermez.

**Diğer şıklar:** a) Hata sayısı test sonuçlarını anlatır. Bu sonuçların hangi şartname sürümüne göre değerlendirildiğini belirlemez. · d) Önem derecesi hatanın etkisini belirtir. Geçerli test esasının hangi sürüm olduğunu açıklamaz.

*Kaçırdıysanız tekrar edin: Yapılandırma yönetimi | Tuzak: Near-miss karışıklığı | LO: FL-5.4.1 (K2)*

[Kılavuzda tekrar edin: Yapılandırma yönetimi](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-4-1)



**Soru 6** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A project reviews a short interface description and a large safety analysis using the same rigid meeting format. Reviewers report that neither discussion serves its purpose. Which change addresses the review success factor at issue?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir projede kısa bir arayüz açıklamasıyla geniş bir emniyet analizi aynı katı toplantı biçimiyle gözden geçirilir. Gözden geçiriciler iki tartışmanın da amacına hizmet etmediğini bildirir. Hangi değişiklik ilgili gözden geçirme başarı faktörünü ele alır?

</div>

a) <span lang="en">Keep the same review type for all work products to preserve procedural consistency</span><br><span lang="tr">Süreç tutarlılığı için bütün iş ürünlerinde aynı gözden geçirme türünü korumak</span>

b) <span lang="en">Evaluate reviewers by the number of disagreements they raise during each meeting</span><br><span lang="tr">Gözden geçiricileri her toplantıda dile getirdikleri anlaşmazlık sayısına göre değerlendirmek</span>

c) <span lang="en">Replace individual preparation with a longer meeting for every work product</span><br><span lang="tr">Her iş ürününde bireysel hazırlığın yerine daha uzun bir toplantı koymak</span>

d) <span lang="en">Choose review types suited to the objectives, work products and participants</span><br><span lang="tr">Hedeflere, iş ürünlerine ve katılımcılara uygun gözden geçirme türlerini seçmek</span>

Bir seçenek seçin.

**Soru 6 — Doğru cevap: d**

**Neden doğru:** Uygun gözden geçirme türü hedeflere, iş ürününe ve katılımcılara bağlıdır. Kısa bir arayüz açıklamasıyla geniş bir emniyet analizine aynı biçimi dayatmak, farklı ihtiyaçların karşılanmasını engelleyebilir.

**En cazip yanlış (near-miss) — a:** Tutarlı bir sürecin yönetimi kolay görünebildiği için caziptir. Ancak biçimsel tutarlılık, amaca uygun olmayan bir gözden geçirme türünün seçilmesini haklı çıkarmaz.

**Diğer şıklar:** b) Katılımcıların performansını anlaşmazlık sayısıyla ölçmek gözden geçirmenin amacı değildir ve açık tartışmayı engelleyebilir. · c) Daha uzun toplantı, uygun bireysel hazırlığın veya amaca uygun tür seçiminin yerine geçmez.

*Kaçırdıysanız tekrar edin: Geri bildirim ve gözden geçirme süreci | Tuzak: Kaynak bilgi eksiği | LO: FL-3.2.5 (K1)*

[Kılavuzda tekrar edin: Geri bildirim ve gözden geçirme süreci](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-3.html#fl-3-2-5)



**Soru 7** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>At release planning, testers propose that the team clarify acceptance conditions while discussing candidate user stories. A developer says this must wait until iteration tasks are assigned. Which response is appropriate?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Sürüm planlamasında test uzmanları, aday kullanıcı hikayeleri konuşulurken kabul koşullarının netleştirilmesini önerir. Bir geliştirici bunun döngü görevleri atanana kadar beklemesi gerektiğini söyler. Hangi yanıt uygundur?

</div>

a) <span lang="en">Testers can help write testable stories and acceptance criteria during release planning</span><br><span lang="tr">Test uzmanları sürüm planlamasında test edilebilir hikayelerin ve kabul kriterlerinin yazılmasına yardım edebilir.</span>

b) <span lang="en">Testers must postpone acceptance criteria for stories until the iteration's test execution has finished</span><br><span lang="tr">Test uzmanları hikayelerin kabul kriterlerini döngünün test koşumu tamamlanana kadar ertelemelidir.</span>

c) <span lang="en">Testers should replace release planning with the detailed testing tasks for one iteration</span><br><span lang="tr">Test uzmanları sürüm planlamasının yerine bir döngünün ayrıntılı test görevlerini koymalıdır.</span>

d) <span lang="en">Testers can contribute to release planning by reporting the final release's executed test results</span><br><span lang="tr">Test uzmanları son sürümün koşulmuş test sonuçlarını bildirerek sürüm planlamasına katkı verebilir.</span>

Bir seçenek seçin.

**Soru 7 — Doğru cevap: a**

**Neden doğru:** Test uzmanları sürüm planlamasında test edilebilir kullanıcı hikayelerinin ve kabul kriterlerinin yazılmasına katılabilir. Döngü planlamasındaki ayrıntılı görev dağılımı farklı bir katkıdır; hikayenin test edilebilirliğini konuşmak onun atanmasını beklemek zorunda değildir.

**En cazip yanlış (near-miss) — c:** Ayrıntılı test görevleri de planlama işi olduğundan caziptir. Ancak bir döngünün görevlerini belirlemek, daha geniş sürüm planlamasının yerine geçmez. Planlama düzeyleri karıştırılmıştır.

**Diğer şıklar:** b) Test koşumunun bitmesini beklemek, hikayenin test edilebilirliğini planlama sırasında desteklemek için geç kalır. · d) Henüz planlanan sürümün tamamlanmış son test sonuçları o aşamada mevcut değildir.

*Kaçırdıysanız tekrar edin: Test planlama | Tuzak: Near-miss karışıklığı | LO: FL-5.1.2 (K1)*

[Kılavuzda tekrar edin: Test planlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-1-2)



**Soru 8** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>What do TDD, ATDD and BDD have in common?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

TDD, ATDD ve BDD yaklaşımlarının ortak özelliği nedir?

</div>

a) <span lang="en">Tests are defined before the code that satisfies them is written</span><br><span lang="tr">Testler, onları karşılayan kod yazılmadan önce tanımlanır.</span>

b) <span lang="en">They all require a test automation framework to be in place</span><br><span lang="tr">Üçü de kurulmuş bir test otomasyon çatısını gerektirir.</span>

c) <span lang="en">They all express their tests in the Given/When/Then format</span><br><span lang="tr">Üçü de testlerini Given/When/Then biçiminde ifade eder.</span>

d) <span lang="en">They all start from the source code and derive tests from its structure</span><br><span lang="tr">Üçü de kaynak koddan başlayıp testleri onun yapısından türetir.</span>

Bir seçenek seçin.

**Soru 8 — Doğru cevap: a**

**Neden doğru:** Bu önce test yaklaşımları, ilgili uygulama kodundan önce testleri tanımlar. Test güdümlü yazılım geliştirme (TDD), kabul testi güdümlü yazılım geliştirme (ATDD) ve davranış güdümlü yazılım geliştirme (BDD), test esası ve ifade biçimi bakımından farklılaşabilir.

**En cazip yanlış (near-miss) — c:** Given/When/Then biçimi BDD ile ilişkili olduğundan caziptir. Ancak bu biçim üç yaklaşımın tamamında zorunlu değildir; ortak nokta testin koddan önce tanımlanmasıdır.

**Diğer şıklar:** b) Bir otomasyon çatısının önceden kurulmuş olması üç yaklaşımın ortak tanımlayıcı koşulu değildir. · d) Mevcut kaynak kodun yapısından test türetmek beyaz kutu tekniklerini anlatır. Bu yaklaşımların ortak önce test sırasını açıklamaz.

*Kaçırdıysanız tekrar edin: Yaşam döngüsü bağlamında test | Tuzak: Near-miss karışıklığı | LO: FL-2.1.3 (K1)*

[Kılavuzda tekrar edin: Yaşam döngüsü bağlamında test](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-1-3)



**Soru 9** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A team uses three-point estimation for a test activity. The optimistic estimate is 7 person-hours, the most likely estimate is 13, and the pessimistic estimate is 31. The team allocates the weighted expected effort plus one standard deviation. What effort should it allocate?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir ekip test aktivitesi için üç noktalı tahminleme kullanır. İyimser tahmin 7 kişi-saat, en olası tahmin 13, kötümser tahmin 31’dir. Ekip, ağırlıklı beklenen efora bir standart sapma ekleyerek kaynak ayırır. Kaç kişi-saat ayırmalıdır?

</div>

a) <span lang="en">15 person-hours</span><br><span lang="tr">15 kişi-saat</span>

b) <span lang="en">19 person-hours</span><br><span lang="tr">19 kişi-saat</span>

c) <span lang="en">23 person-hours</span><br><span lang="tr">23 kişi-saat</span>

d) <span lang="en">21 person-hours</span><br><span lang="tr">21 kişi-saat</span>

Bir seçenek seçin.

**Soru 9 — Doğru cevap: b**

**Neden doğru:** Adım adım: 1. Ağırlıklı tahmini E = (7 + 4 × 13 + 31) / 6 = 90/6 = 15 kişi-saat olarak hesaplayın. 2. Standart sapma SD = (31 − 7) / 6 = 4 kişi-saattir. 3. İstenen bir standart sapmayı ekleyin: 15 + 4 = 19 kişi-saat. Bu kaynak ayırma tercihi gerçek eforun kesin 19 olacağını garanti etmez.

**En cazip yanlış (near-miss) — a:** 15 doğru ağırlıklı tahmin olduğu için caziptir. Ancak soru tahminin kendisini değil, ona bir standart sapma eklenerek ayrılacak eforu ister. 15 seçeneği istenen ek payı atlar.

**Diğer şıklar:** c) 23 = 15 + 2 × 4 sonucudur. Bir yerine iki standart sapma eklenmiştir. · d) 21 = 17 + 4 sonucudur. 17, ağırlıksız (7 + 13 + 31) / 3 ortalamasıdır; istenen ağırlıklı tahmin kullanılmamıştır.

*Kaçırdıysanız tekrar edin: Test planlama | Tuzak: Prosedür hatası | LO: FL-5.1.4 (K3)*

[Kılavuzda tekrar edin: Test planlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-1-4)



**Soru 10** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Late in the release, specialists run load tests against the completed system, probe it for security weaknesses and measure response times against the service targets. None of these results guide feature development; they judge the finished product from a technical standpoint. Which testing quadrant is this?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Sürümün sonlarına doğru uzmanlar tamamlanmış sistemde yük testleri koşar, güvenlik zayıflıklarını araştırır ve yanıt sürelerini hizmet hedefleriyle karşılaştırır. Bu sonuçlar özelliklerin geliştirilmesine yön vermez; bitmiş ürünü teknik açıdan değerlendirir. Bu hangi test çeyreğidir?

</div>

a) <span lang="en">Q1 — technology-facing, support the team</span><br><span lang="tr">Q1 — teknoloji odaklı, ekibi destekler</span>

b) <span lang="en">Q2 — business-facing, support the team</span><br><span lang="tr">Q2 — iş odaklı, ekibi destekler</span>

c) <span lang="en">Q3 — business-facing, critique the product</span><br><span lang="tr">Q3 — iş odaklı, ürünü eleştirir</span>

d) <span lang="en">Q4 — technology-facing, critique the product</span><br><span lang="tr">Q4 — teknoloji odaklı, ürünü eleştirir</span>

Bir seçenek seçin.

**Soru 10 — Doğru cevap: d**

**Neden doğru:** Q4 teknoloji odaklıdır ve ürünü eleştirir. Yük, güvenlik ve yanıt süresi değerlendirmeleri burada tamamlanmış ürünün teknik özelliklerini sınar. Çeyreği belirleyen yalnız zaman değil, teknik bakış ve ürünü değerlendirme amacının birlikteliğidir.

**En cazip yanlış (near-miss) — a:** Q1 de teknoloji odaklı olduğu için caziptir. Ancak Q1 geliştirmeye yön veren testlerle ekibi destekler. Kökteki testler geliştirmeyi yönlendirmek yerine bitmiş ürünü değerlendirir.

**Diğer şıklar:** b) Q2 iş dilinde geliştirmeye yön vererek ekibi destekler. Verilen teknik değerlendirme bu amaçta değildir. · c) Q3 ürünü iş açısından değerlendirir. Kökteki yük, güvenlik ve yanıt süresi bakışı tekniktir.

*Kaçırdıysanız tekrar edin: Test planlama | Tuzak: Near-miss karışıklığı | LO: FL-5.1.7 (K2)*

[Kılavuzda tekrar edin: Test planlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-1-7)


### S11–S20



**Soru 11** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A test level has met its planned coverage target and has no unresolved defects above the agreed limit. The environment and test basis were available before testing began. Which statement correctly uses these facts in a completion decision?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir test seviyesi planlanan kapsam hedefine ulaşmıştır ve üzerinde anlaşılmış sınırın üzerinde çözümlenmemiş hata yoktur. Ortam ve test esası test başlamadan önce hazırdır. Hangi ifade bu bilgileri tamamlama kararında doğru kullanır?

</div>

a) <span lang="en">Environment availability is the achieved test thoroughness needed to justify completion</span><br><span lang="tr">Ortamın hazır olması, tamamlamayı gerekçelendiren ulaşılmış test derinliğidir.</span>

b) <span lang="en">Coverage and unresolved-defect thresholds are exit evidence; earlier availability supported entry</span><br><span lang="tr">Kapsam ve çözümlenmemiş hata eşikleri çıkış kanıtıdır; önceden hazır olma girişi desteklemiştir.</span>

c) <span lang="en">Test-basis availability replaces the coverage target when deciding whether testing is complete</span><br><span lang="tr">Test esasının hazır olması, tamamlamaya karar verirken kapsam hedefinin yerini alır.</span>

d) <span lang="en">An approved budget is stronger exit evidence than achieved coverage and residual defects</span><br><span lang="tr">Onaylı bütçe, ulaşılan kapsam ve kalan hatalardan daha güçlü çıkış kanıtıdır.</span>

Bir seçenek seçin.

**Soru 11 — Doğru cevap: b**

**Neden doğru:** Ulaşılmış kapsam ve çözümlenmemiş hata eşikleri çıkış kriterlerinin değerlendirilmesine kanıt sağlar. Ortam ve test esasının hazır olması ise daha önce başlama kararını, yani giriş kriterlerini desteklemiştir. Hazır olma ile tamamlanmış test sonuçları ayrılmalıdır.

**En cazip yanlış (near-miss) — a:** Çalışan ortam test için gerekli olduğundan caziptir. Ancak ortamın hazır olması başlama koşuludur; planlanan test derinliğine ulaşıldığını göstermez.

**Diğer şıklar:** c) Test esasının mevcut olması, planlanan testlerin tamamlandığını göstermez ve kapsam hedefinin yerine geçmez. · d) Kaynakların onaylanması, elde edilmiş test sonuçlarını veya kalan hataların değerlendirilmesini karşılamaz.

*Kaçırdıysanız tekrar edin: Test planlama | Tuzak: Near-miss karışıklığı | LO: FL-5.1.3 (K2)*

[Kılavuzda tekrar edin: Test planlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-1-3)



**Soru 12** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>An integer batch-size field has three ordered partitions: values below 80 are rejected, 80 through 82 are accepted, and values above 82 are rejected. Using 2-value BVA, a tester has run 79, 80, 82 and 83. What boundary coverage has been achieved?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir tamsayı parti büyüklüğü alanının sıralı üç payı vardır: 80 altı reddedilir, 80–82 dahil kabul edilir, 82 üzeri reddedilir. Test uzmanı **2 değerli sınır değer analizi (SDA)** kullanarak 79, 80, 82 ve 83 değerlerini koşmuştur. Hangi sınır kapsamı sağlanmıştır?

</div>

a) <span lang="en">50%, because the two invalid partitions are excluded from boundary coverage</span><br><span lang="tr">%50; çünkü iki geçersiz pay sınır kapsamının dışında bırakılır.</span>

b) <span lang="en">About 57%, because coverage is calculated against the larger 3-value BVA set</span><br><span lang="tr">Yaklaşık %57; çünkü kapsam daha büyük 3 değerli SDA kümesine göre hesaplanır.</span>

c) <span lang="en">100%, because both adjacent-partition boundary pairs have been exercised</span><br><span lang="tr">%100; çünkü bitişik paylardaki her iki sınır çifti de sınanmıştır.</span>

d) <span lang="en">80%, because the accepted interval contains an additional integer value</span><br><span lang="tr">%80; çünkü kabul edilen aralıkta bir tamsayı daha vardır.</span>

Bir seçenek seçin.

**Soru 12 — Doğru cevap: c**

**Neden doğru:** Adım adım: 1. Bitişik payların sınır çiftlerini 79/80 ve 82/83 olarak belirleyin. 2. Gerekli ayrı kapsam öğelerini {79, 80, 82, 83} olarak yazın. 3. Koşulan değerlerin dördünü de kapsadığını görün: 4/4 × 100 = %100. Kapsam hesabı kökte belirtilen 2 değerli SDA varyantına dayanır.

**En cazip yanlış (near-miss) — b:** 3 değerli SDA da geçerli bir teknik olduğundan caziptir. Ancak o varyant {78, 79, 80, 81, 82, 83, 84} olmak üzere yedi ayrı öğe verir ve 4/7 yaklaşık %57 eder. Kök 2 değerli SDA ister; gereken dört öğe zaten kapsanmıştır.

**Diğer şıklar:** a) Geçersiz paylar sınır analizine dahildir. İki geçersiz test değerini paydan düşürüp paydayı dört bırakmak, yanlış 2/4 = %50 sonucunu üretir. · d) İç değer 81 bu varyantın ek sınır öğesi değildir. Onu paydaya ekleyip 4/5 = %80 hesaplamak yanlış kümeyi kullanır.

*Kaçırdıysanız tekrar edin: Kara kutu test teknikleri | Tuzak: Prosedür hatası | LO: FL-4.2.2 (K3)*

[Kılavuzda tekrar edin: Kara kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-2-2)



**Soru 13** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A small team assigns one person to both test management and testing. Another team divides test management responsibilities among several people. A reviewer rejects both arrangements because each role must correspond to exactly one person. How should this claim be assessed?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Küçük bir ekip, bir kişiye hem test yönetimi hem test rolünü verir. Başka bir ekip test yönetimi sorumluluklarını birkaç kişi arasında paylaştırır. Bir gözden geçirici, her rolün tam bir kişiye karşılık gelmesi gerektiğini söyleyerek iki düzenlemeyi de reddeder. Bu iddia nasıl değerlendirilmelidir?

</div>

a) <span lang="en">It is correct: a role must have one exclusive owner for every activity</span><br><span lang="tr">Doğrudur; her aktivitede bir rolün kendisine ayrılmış tek sahibi olmalıdır.</span>

b) <span lang="en">It is incorrect: roles group responsibilities and can be combined or distributed</span><br><span lang="tr">Yanlıştır; roller sorumluluk gruplarıdır ve birleştirilebilir ya da paylaştırılabilir.</span>

c) <span lang="en">It is correct for the small team, but responsibilities may be split in the other</span><br><span lang="tr">Küçük ekip için doğrudur; diğer ekipte ise sorumluluklar paylaştırılabilir.</span>

d) <span lang="en">It is incorrect because test management and testing are interchangeable roles</span><br><span lang="tr">Yanlıştır; çünkü test yönetimi ve test birbirinin yerine geçen rollerdir.</span>

Bir seçenek seçin.

**Soru 13 — Doğru cevap: b**

**Neden doğru:** Roller sorumluluk gruplarını tanımlar. Bağlama göre bir kişi iki rolü de üstlenebilir veya birkaç kişi bir rolün sorumluluklarını paylaşabilir. Rolün tanımı ile onu üstlenen kişi sayısı ayrı konulardır.

**En cazip yanlış (near-miss) — c:** Büyük ekipte sorumluluk paylaşımının uygun olabileceğini kabul ettiği için caziptir. Ancak küçük ekipte iki rolün aynı kişide birleşmesi de uygun olabilir; ilk düzenlemeyi reddetmek için verilen gerekçe geçersizdir.

**Diğer şıklar:** a) Ders programı rollerin kişilerle bire bir ve dışlayıcı biçimde eşleştirilmesini zorunlu kılmaz. · d) Aynı kişi üstlense bile iki rolün sorumlulukları farklı kalır. Birleşebilmeleri, birbirinin yerine geçtikleri anlamına gelmez.

*Kaçırdıysanız tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller | Tuzak: Kaynak bilgi eksiği | LO: FL-1.4.5 (K2)*

[Kılavuzda tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-4-5)



**Soru 14** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A print shop accepts the following criterion: "An order can be cancelled without a handling fee at least 36 hours before its scheduled collection. A later cancellation incurs the handling fee."</p>
<p>Collection is scheduled for Wednesday 21 October 2026 at 14:00. Which test case correctly checks a cancellation that incurs the fee?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir basımevi şu kabul kriterini kullanır: “Sipariş, planlanan teslim alma zamanından en az 36 saat önce iptal edilirse işlem ücreti alınmaz. Daha geç iptalde işlem ücreti uygulanır.”

Teslim alma zamanı 21 Ekim 2026 Çarşamba saat 14.00'tür. Hangi test senaryosu ücret uygulanacak bir iptali doğru kontrol eder?

</div>

a) <span lang="en">Cancel Tuesday 20 October at 01:00; expect the handling fee</span><br><span lang="tr">20 Ekim Salı saat 01.00’de iptal et; işlem ücreti bekle.</span>

b) <span lang="en">Cancel Tuesday 20 October at 03:00; expect no handling fee</span><br><span lang="tr">20 Ekim Salı saat 03.00’te iptal et; işlem ücreti alınmamasını bekle.</span>

c) <span lang="en">Cancel Tuesday 20 October at 02:00; expect the handling fee</span><br><span lang="tr">20 Ekim Salı saat 02.00’de iptal et; işlem ücreti bekle.</span>

d) <span lang="en">Cancel Tuesday 20 October at 03:00; expect the handling fee</span><br><span lang="tr">20 Ekim Salı saat 03.00’te iptal et; işlem ücreti bekle.</span>

Bir seçenek seçin.

**Soru 14 — Doğru cevap: d**

**Neden doğru:** Adım adım: 1. Salı 14.00 ile Çarşamba 14.00 arasında 24 saat vardır. 2. Salı 03.00 ile Salı 14.00 arasındaki 11 saati ekleyin: 35 saat. 3. 35, ücretsiz iptal için gereken 36 saatten azdır; işlem ücreti beklenir. Test senaryosu zamanla birlikte doğru beklenen sonucu da belirtmelidir.

**En cazip yanlış (near-miss) — c:** Tam sınır anını kullandığı için caziptir. Ancak Salı 02.00 ile Çarşamba 14.00 arasında tam 36 saat vardır. “En az” ifadesi eşitliği kapsar; bu anda iptal ücretsizdir.

**Diğer şıklar:** a) Salı 01.00, teslim almadan 37 saat öncedir. Ücretsiz iptal koşulu sağlanır; ücret beklemek yanlıştır. · b) Salı 03.00, teslim almadan 35 saat öncedir. Zaman ücretli iptale uygundur, ancak verilen beklenen sonuç ücreti yanlış biçimde kaldırır.

*Kaçırdıysanız tekrar edin: İş birliğine dayalı test yaklaşımları | Tuzak: Prosedür hatası | LO: FL-4.5.3 (K3)*

[Kılavuzda tekrar edin: İş birliğine dayalı test yaklaşımları](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-5-3)



**Soru 15** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Developers say that component tests written by their colleagues already count as fully independent external testing. A separate testing organization is also involved. Which assessment explains the difference?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Geliştiriciler, çalışma arkadaşlarının yazdığı bileşen testlerinin bütünüyle bağımsız dış test sayıldığını söyler. Çalışmaya ayrı bir test kuruluşu da katılmaktadır. Hangi değerlendirme aradaki farkı açıklar?

</div>

a) <span lang="en">Colleagues and a separate organization offer the same independence because neither wrote the code</span><br><span lang="tr">Kodu ikisi de yazmadığından çalışma arkadaşları ve ayrı kuruluş aynı bağımsızlığı sağlar.</span>

b) <span lang="en">Colleagues offer greater independence because they can consult the author during testing</span><br><span lang="tr">Test sırasında yazara danışabildiklerinden çalışma arkadaşları daha fazla bağımsızlık sağlar.</span>

c) <span lang="en">A separate organization has less independence because its testers lack the internal code history</span><br><span lang="tr">İç kod geçmişini bilmediklerinden ayrı kuruluşun test uzmanları daha az bağımsızdır.</span>

d) <span lang="en">Colleagues offer some independence, while a separate organization offers a higher degree</span><br><span lang="tr">Çalışma arkadaşları bir ölçüde bağımsızdır; ayrı kuruluş daha yüksek bağımsızlık sağlar.</span>

Bir seçenek seçin.

**Soru 15 — Doğru cevap: d**

**Neden doğru:** Bağımsızlığın dereceleri vardır. Çalışma arkadaşının yaptığı test, yazarın kendi testinden daha bağımsızdır. Ayrı bir kuruluşun test uzmanları ise yazarlardan daha yüksek derecede bağımsızlık sağlar. Yazarı olmamak bütün düzenlemeleri eşit yapmaz.

**En cazip yanlış (near-miss) — a:** İki durumda da testi kodun yazarı yapmadığı için caziptir. Ancak aynı ekipte olmakla ayrı bir kuruluşta olmak farklı bağımsızlık dereceleridir; ortak özellik bu farkı ortadan kaldırmaz.

**Diğer şıklar:** b) Yazara erişebilmek iş birliğini destekleyebilir. Bu erişim, kuruluş bakımından daha bağımsız olunduğunu göstermez. · c) İç geçmişi bilmemek alan bilgisiyle ilgili bir sınırlama olabilir. Ayrı kuruluşta bulunmanın sağladığı bağımsızlık derecesini azaltmaz.

*Kaçırdıysanız tekrar edin: Testte temel beceriler ve iyi uygulamalar | Tuzak: Kaynak bilgi eksiği | LO: FL-1.5.3 (K2)*

[Kılavuzda tekrar edin: Testte temel beceriler ve iyi uygulamalar](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-5-3)



**Soru 16** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A test charter specifies "explore interrupted uploads for 45 minutes" without prescribing the sequence of clicks. A reviewer rejects it as incomplete because it lacks a fixed procedure. Which assessment fits session-based exploratory testing?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir test başlatma belgesi “kesilen yüklemeleri 45 dakika araştırın” der; tıklama sırasını belirtmez. Bir gözden geçirici, sabit prosedürü olmadığı için belgeyi eksik bulur. Hangi değerlendirme oturuma dayalı keşif testine uygundur?

</div>

a) <span lang="en">The rejection is justified because every test charter must specify all execution steps</span><br><span lang="tr">Her test başlatma belgesi bütün koşum adımlarını belirtmek zorunda olduğundan ret haklıdır.</span>

b) <span lang="en">The charter can guide the objectives and time-box while leaving test design to the tester</span><br><span lang="tr">Belge hedefleri ve süre sınırını yönlendirebilir; test tasarımını test uzmanına bırakabilir.</span>

c) <span lang="en">The rejection is justified because a time-box is used for scripted testing rather than exploration</span><br><span lang="tr">Süre sınırı keşif yerine betikli testte kullanıldığı için ret haklıdır.</span>

d) <span lang="en">The charter must be replaced by a statement-coverage target before the session can begin</span><br><span lang="tr">Oturum başlamadan belge yerine bir komut kapsamı hedefi konulmalıdır.</span>

Bir seçenek seçin.

**Soru 16 — Doğru cevap: b**

**Neden doğru:** Oturuma dayalı keşif testi, süre sınırı ve test hedeflerini içeren bir test başlatma belgesi (test charter) kullanır. Sabit bir eylem dizisi zorunlu değildir; test uzmanı keşif sırasında test tasarlar ve uygular.

**En cazip yanlış (near-miss) — a:** Belge oturumdan önce hazırlandığı için bir prosedür gibi algılanabilir. Ancak test başlatma belgesi her eylemi önceden belirlemek zorunda değildir; hedef ve yön sağlar.

**Diğer şıklar:** c) Belirli bir süre sınırı oturuma dayalı keşif çalışmasıyla uyumludur. Betikli teste özgü değildir. · d) Komut kapsamı bir yapısal ölçüttür. Keşfin hedeflerini belirleyen belgenin yerine geçirilmesi gerekmez.

*Kaçırdıysanız tekrar edin: Tecrübeye dayalı test teknikleri | Tuzak: Kaynak bilgi eksiği | LO: FL-4.4.2 (K2)*

[Kılavuzda tekrar edin: Tecrübeye dayalı test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-4-2)



**Soru 17** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Which statement about testing and quality management is correct?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Test ve kalite yönetimiyle ilgili hangi ifade doğrudur?

</div>

a) <span lang="en">Testing is a form of quality control, and QC and QA are both part of quality management</span><br><span lang="tr">Test kalite kontrolün bir biçimidir; kontrol ve güvence kalite yönetiminin parçalarıdır.</span>

b) <span lang="en">Quality management is one of the several activities that make up the test process</span><br><span lang="tr">Kalite yönetimi, test sürecini oluşturan çeşitli aktivitelerden biridir.</span>

c) <span lang="en">QA is a form of quality control that concentrates on the quality of the product</span><br><span lang="tr">Kalite güvencesi, ürünün kalitesine odaklanan bir kalite kontrol biçimidir.</span>

d) <span lang="en">Testing belongs to quality management, while QA is positioned outside of it</span><br><span lang="tr">Test kalite yönetimine dahildir; kalite güvencesi ise onun dışında yer alır.</span>

Bir seçenek seçin.

**Soru 17 — Doğru cevap: a**

**Neden doğru:** Kalite yönetimi hem kalite güvencesini (QA) hem kalite kontrolü (QC) kapsar. Test, kalite kontrolün önemli bir biçimidir. Kalite güvencesi süreçlere ve hataların önlenmesine odaklanır; kalite kontrolün alt başlığı değildir.

**En cazip yanlış (near-miss) — c:** Doğru kavramları birbirine yakın bir düzenle verdiği için caziptir. Ancak kalite güvencesini kalite kontrolün içine yerleştirir ve ona ürün odaklı bir amaç yükler. Kalite güvencesi süreç odaklıdır.

**Diğer şıklar:** b) Hiyerarşiyi tersine çevirir. Test süreci kalite yönetimini kapsamaz; onun içinde yer alır. · d) Kalite güvencesini kalite yönetiminin dışında bırakır. Oysa kalite güvencesi de kalite yönetiminin parçasıdır.

*Kaçırdıysanız tekrar edin: Test neden gereklidir? | Tuzak: Kaynak bilgi eksiği | LO: FL-1.2.2 (K1)*

[Kılavuzda tekrar edin: Test neden gereklidir?](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-2-2)



**Soru 18** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Under the whole team approach, what determines whether a team member can perform a particular task?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Tüm ekip yaklaşımında (whole team approach), bir ekip üyesinin belirli bir görevi yapabilmesini ne belirler?

</div>

a) <span lang="en">The member's original job title, regardless of their relevant knowledge</span><br><span lang="tr">İlgili bilgisinden bağımsız olarak üyenin başlangıçtaki görev unvanı</span>

b) <span lang="en">The member's location in a separate testing organization</span><br><span lang="tr">Üyenin ayrı bir test kuruluşunda bulunması</span>

c) <span lang="en">The member's seniority relative to the other team members</span><br><span lang="tr">Üyenin diğer ekip üyelerine göre kıdemi</span>

d) <span lang="en">The member's necessary knowledge and skills for that task</span><br><span lang="tr">Üyenin görev için gerekli bilgi ve becerilere sahip olması</span>

Bir seçenek seçin.

**Soru 18 — Doğru cevap: d**

**Neden doğru:** Gerekli bilgi ve becerilere sahip bir ekip üyesi görevi yerine getirebilir. Tüm ekip yaklaşımı, işi başlangıçtaki görev unvanlarıyla katı biçimde sınırlandırmaz. Görev ile ilgili yetkinlik esas alınır.

**En cazip yanlış (near-miss) — a:** Görev unvanı uzmanlık hakkında fikir verebildiği için caziptir. Ancak unvanın kendisi, gerekli bilgi ve becerilerin yerine geçmez; görevler başlangıçtaki unvana göre sabitlenmez.

**Diğer şıklar:** b) Ayrı bir test kuruluşunda bulunmak, ekip içindeki görevi üstlenmenin koşulu değildir. · c) Kıdem tek başına görevin gerektirdiği bilgi ve becerilere sahip olunduğunu göstermez.

*Kaçırdıysanız tekrar edin: Testte temel beceriler ve iyi uygulamalar | Tuzak: Kaynak bilgi eksiği | LO: FL-1.5.2 (K1)*

[Kılavuzda tekrar edin: Testte temel beceriler ve iyi uygulamalar](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-5-2)



**Soru 19** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Complete BOTH statements about good testing practices that apply across SDLC models.</p>
<ol type="1">
<li>Test analysis and test design for a level begin _____.</li>
<li>Testers start reviewing work products _____.</li>
</ol>
<p>Which pair completes the statements correctly?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Yazılım geliştirme yaşam döngüsü modellerinin tümünde geçerli iyi test uygulamalarıyla ilgili **İKİ** ifadeyi de tamamlayın.

1. Bir test seviyesinin test analizi ve test tasarımı _____ başlar.
2. Test uzmanları iş ürünlerini gözden geçirmeye _____ başlar.

Hangi çift ifadeleri doğru tamamlar?

</div>

a) <span lang="en">During test execution; when approved final versions are available</span><br><span lang="tr">Test koşumu sırasında; onaylanmış son sürümler hazır olduğunda</span>

b) <span lang="en">During test completion; when the corresponding code has been released</span><br><span lang="tr">Test tamamlama sırasında; ilgili kod yayımlandığında</span>

c) <span lang="en">During the corresponding development phase; when draft versions are available</span><br><span lang="tr">İlgili geliştirme aşamasında; taslak sürümler hazır olduğunda</span>

d) <span lang="en">During test execution; when draft versions are available</span><br><span lang="tr">Test koşumu sırasında; taslak sürümler hazır olduğunda</span>

Bir seçenek seçin.

**Soru 19 — Doğru cevap: c**

**Neden doğru:** Test analizi ve tasarımı ilgili geliştirme aşamasıyla birlikte başlar. İş ürünlerinin taslakları hazır olduğunda gözden geçirmeye başlanabilir. Doğru çift bu iki erken test uygulamasını birlikte korur; soru iki boşluğun da doğru tamamlanmasını ister.

**En cazip yanlış (near-miss) — d:** Taslakların hazır olması gözden geçirme için doğru zamandır. Ancak ilk boşluk yanlıştır: analiz ve tasarımı test koşumuna kadar ertelemek erken başlama uygulamasını karşılamaz.

**Diğer şıklar:** a) İki işi de erteler. Analiz ve tasarım koşumdan önce başlayabilir; gözden geçirmeler son onayı beklemek zorunda değildir. · b) Tamamlama ve kodun yayını, erken analiz, tasarım ve taslak inceleme fırsatlarından sonra gelir.

*Kaçırdıysanız tekrar edin: Yaşam döngüsü bağlamında test | Tuzak: Dikkatsiz okuma | LO: FL-2.1.2 (K1)*

[Kılavuzda tekrar edin: Yaşam döngüsü bağlamında test](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-1-2)



**Soru 20** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A loyalty program lets customers redeem 1 to 500 points per order: redemptions of 1–100 points get no bonus, redemptions of 101–500 points get a 5% bonus, and amounts of 0 or less, or more than 500, are rejected. Which set of test values covers every equivalence partition exactly once?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir sadakat programı müşterilerin sipariş başına 1–500 puan kullanmasına izin verir. 1–100 puan için bonus verilmez; 101–500 puan için %5 bonus verilir. 0 veya altındaki ve 500 üzerindeki miktarlar reddedilir. Hangi test değeri kümesi her denklik payını **tam bir kez** kapsar?

</div>

a) <span lang="en">0, 50, 250, 600</span><br><span lang="tr">0, 50, 250, 600</span>

b) <span lang="en">50, 250</span><br><span lang="tr">50, 250</span>

c) <span lang="en">0, 600</span><br><span lang="tr">0, 600</span>

d) <span lang="en">1, 100, 101, 500</span><br><span lang="tr">1, 100, 101, 500</span>

Bir seçenek seçin.

**Soru 20 — Doğru cevap: a**

**Neden doğru:** Adım adım: 1. Payları belirleyin: ≤0 geçersiz, 1–100 bonussuz, 101–500 %5 bonuslu, >500 geçersiz. 2. 0, 50, 250 ve 600 değerlerini sırayla bu dört paya yerleştirin. 3. Her payda tam bir değer bulunduğunu kontrol edin. Tek puan girdisinin her testte tek değeri vardır; farklı payları bir testte birleştirmek burada uygulanamaz, farklı çok girdili bir problem gerektirir.

**En cazip yanlış (near-miss) — d:** Sınır değerleri güçlü test adayları gibi göründüğü için caziptir. Ancak 1 ve 100 aynı paya, 101 ve 500 diğer geçerli paya düşer. İki geçersiz pay hiç sınanmaz; sorulan sınır testi değil her payın tam bir kez kapsanmasıdır.

**Diğer şıklar:** b) İki geçerli payı kapsar; reddedilen miktarlara ait iki geçersiz payı kapsamaz. · c) İki geçersiz payı kapsar; kabul edilen davranışların iki geçerli payını kapsamaz.

*Kaçırdıysanız tekrar edin: Kara kutu test teknikleri | Tuzak: Prosedür hatası | LO: FL-4.2.1 (K3)*

[Kılavuzda tekrar edin: Kara kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-2-1)


### S21–S30



**Soru 21** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>During a review, one participant keeps the discussion on time, ensures that quieter people can contribute, and records the newly agreed actions. Which assessment of this assignment is correct?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir gözden geçirmede katılımcılardan biri tartışmanın süresini gözetir, daha sessiz kişilerin katkıda bulunabilmesini sağlar ve yeni kararlaştırılan eylemleri kaydeder. Bu görevlendirmeyle ilgili hangi değerlendirme doğrudur?

</div>

a) <span lang="en">The participant is the author because moderating discussion and recording actions correct the work product</span><br><span lang="tr">Tartışmayı yönetmek ve eylemleri kaydetmek iş ürününü düzelttiğinden bu katılımcı yazardır.</span>

b) <span lang="en">The participant combines moderator and scribe responsibilities; review participants may hold several roles</span><br><span lang="tr">Katılımcı moderatör ve katip sorumluluklarını birleştirir; katılımcılar birden çok rol üstlenebilir.</span>

c) <span lang="en">The participant is the manager because the meeting discussion determines the review budget</span><br><span lang="tr">Toplantıdaki tartışma gözden geçirme bütçesini belirlediğinden bu katılımcı yöneticidir.</span>

d) <span lang="en">The participant combines reviewer and author responsibilities because each meeting action is a content correction</span><br><span lang="tr">Her toplantı eylemi bir içerik düzeltmesi olduğundan katılımcı gözden geçirici ve yazar rollerini birleştirir.</span>

Bir seçenek seçin.

**Soru 21 — Doğru cevap: b**

**Neden doğru:** Süreyi yönetmek ve güvenli bir tartışma ortamı sağlamak moderatörün sorumluluklarıdır. Kararlaştırılan eylemleri kaydetmek katibin sorumluluğudur. Bir katılımcı birden çok rol üstlenebildiği için bu iki sorumluluk aynı kişide birleşebilir.

**En cazip yanlış (near-miss) — a:** Yazar değişikliklerle ilgili tartışmalara katılabileceği için caziptir. Ancak anlatılan görevler iş ürününü yazmayı veya düzeltmeyi içermez; tartışmayı kolaylaştırmakla sonucu kaydetmektir.

**Diğer şıklar:** c) Kaynak sağlamak veya gözden geçirme bütçesini kararlaştırmak kökte anlatılmamıştır. Tartışmayı yönetmek bu kararları vermek değildir. · d) Her eylem içerik düzeltmesi değildir. Tartışmayı kolaylaştırmak ve sonucunu kaydetmek, içeriği inceleme ve düzeltme sorumluluklarından farklıdır.

*Kaçırdıysanız tekrar edin: Geri bildirim ve gözden geçirme süreci | Tuzak: Near-miss karışıklığı | LO: FL-3.2.3 (K1)*

[Kılavuzda tekrar edin: Geri bildirim ve gözden geçirme süreci](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-3.html#fl-3-2-3)



**Soru 22** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>An author plans a walkthrough to teach colleagues about a new interface. A participant objects to logging anomalies because the meeting has an educational goal. Which response fits this review type?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir yazar yeni bir arayüzü çalışma arkadaşlarına öğretmek için üzerinden geçme (walkthrough) planlar. Bir katılımcı, toplantının eğitim amacı bulunduğu için anomalilerin kaydedilmesine itiraz eder. Hangi yanıt bu gözden geçirme türüne uygundur?

</div>

a) <span lang="en">Accept the objection because an educational walkthrough excludes logging anomalies</span><br><span lang="tr">Eğitim amaçlı üzerinden geçme anomalilerin kaydını dışladığından itirazı kabul etmek</span>

b) <span lang="en">Convert the meeting into an inspection because walkthroughs are limited to presentations</span><br><span lang="tr">Üzerinden geçme sunumlarla sınırlı olduğundan toplantıyı teftişe dönüştürmek</span>

c) <span lang="en">Keep the walkthrough: it can support learning and also identify anomalies</span><br><span lang="tr">Üzerinden geçmeyi sürdürmek; hem öğrenmeyi destekleyebilir hem anomalileri bulabilir.</span>

d) <span lang="en">Replace the author with a moderator because walkthroughs require a moderator to lead</span><br><span lang="tr">Üzerinden geçmeyi moderatör yönetmek zorunda olduğundan yazarın yerine moderatör koymak</span>

Bir seçenek seçin.

**Soru 22 — Doğru cevap: c**

**Neden doğru:** Üzerinden geçme katılımcıları eğitebilir, geri bildirim toplayabilir ve anomalileri tespit edebilir. Eğitim amacı, bulguların kaydedilmesini dışlamaz. Bu amaçlar aynı gözden geçirmede birlikte yer alabilir.

**En cazip yanlış (near-miss) — b:** Teftişler de anomali bulduğu için caziptir. Ancak anomali bulmak üzerinden geçmenin de amaçlarından biri olabilir; bu nedenle türü teftişe çevirmek gerekmez.

**Diğer şıklar:** a) Eğitim ve anomali tespiti aynı üzerinden geçmede birlikte bulunabilir. Bir amaç diğerini dışlamaz. · d) Üzerinden geçmeyi yazar yönetir. Moderatörün yönettiği gözden geçirme türüyle karıştırılmıştır.

*Kaçırdıysanız tekrar edin: Geri bildirim ve gözden geçirme süreci | Tuzak: Near-miss karışıklığı | LO: FL-3.2.4 (K2)*

[Kılavuzda tekrar edin: Geri bildirim ve gözden geçirme süreci](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-3.html#fl-3-2-4)



**Soru 23** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Which statement about regression testing is correct?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Regresyon testiyle ilgili hangi ifade doğrudur?

</div>

a) <span lang="en">Regression test suites run many times and grow over the iterations, which makes them strong candidates for automation</span><br><span lang="tr">Regresyon test takımları çok kez koşulur ve döngüler boyunca büyür; bu nedenle otomasyona güçlü adaydır.</span>

b) <span lang="en">Regression testing is performed to confirm that a specific defect fix has resolved the original problem</span><br><span lang="tr">Regresyon testi, belirli bir hata düzeltmesinin başlangıçtaki problemi çözdüğünü onaylamak için yapılır.</span>

c) <span lang="en">Regression testing targets the changed parts of the system rather than the unchanged ones</span><br><span lang="tr">Regresyon testi, sistemin değişmeyen kısımları yerine değişen kısımlarını hedefler.</span>

d) <span lang="en">Regression testing becomes unnecessary once the development process reaches a high maturity</span><br><span lang="tr">Geliştirme süreci yüksek olgunluğa ulaştığında regresyon testine gerek kalmaz.</span>

Bir seçenek seçin.

**Soru 23 — Doğru cevap: a**

**Neden doğru:** Regresyon test takımları tekrar tekrar koşulur ve ürün geliştikçe genellikle büyür. Tekrar ve büyüyen kapsam, otomasyonu uygun kılabilir. Regresyon testinin amacı değişikliğin olumsuz sonuçlarını bulmaktır; kapsamı etki analiziyle belirlenir.

**En cazip yanlış (near-miss) — b:** Belirli bir düzeltmenin kontrolü gerçek bir test aktivitesi olduğu için caziptir. Ancak bu, onaylama testidir (confirmation testing). Regresyon, değişikliğin olumsuz sonuçlarını araştırır.

**Diğer şıklar:** c) Kapsamı değişen veya değişmeyen kısımlarla dışlayıcı biçimde sınırlamak yanlıştır. Olumsuz sonuçlar değişen bileşende, diğer bileşenlerde, bağlı sistemlerde veya ortamda görülebilir. · d) Süreç olgunluğu, değişikliklerin olumsuz sonuçlarını araştırma ihtiyacını ortadan kaldırmaz.

*Kaçırdıysanız tekrar edin: Test seviyeleri ve test çeşitleri | Tuzak: Near-miss karışıklığı | LO: FL-2.2.3 (K2)*

[Kılavuzda tekrar edin: Test seviyeleri ve test çeşitleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-2-3)



**Soru 24** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Testing of a release has ended. The sponsor wants a summary of what differed from the agreed plan, the quality concerns still outstanding, and improvements for the next release. Which response best meets this request?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir sürümün testleri bitmiştir. Sponsor, kararlaştırılan plandan sapmaların, devam eden kalite kaygılarının ve sonraki sürüm için iyileştirmelerin özetini ister. Hangi yanıt bu isteği **EN İYİ** karşılar?

</div>

a) <span lang="en">Send the next week's planned testing and leave out the completed release's evaluation</span><br><span lang="tr">Sonraki haftanın planlanan testlerini gönderip biten sürümün değerlendirmesini dışarıda bırakmak</span>

b) <span lang="en">Send the daily change in newly reported defects without a release-level assessment</span><br><span lang="tr">Sürüm düzeyinde değerlendirme yapmadan yeni bildirilen hatalardaki günlük değişimi göndermek</span>

c) <span lang="en">Prepare a completion report covering deviations, unmitigated risks and lessons learned</span><br><span lang="tr">Sapmaları, azaltılmamış riskleri ve çıkarılan dersleri içeren tamamlama raporu hazırlamak</span>

d) <span lang="en">Prepare a new execution schedule and treat it as evidence that the release is complete</span><br><span lang="tr">Yeni koşum takvimi hazırlayıp bunu sürümün tamamlandığına ilişkin kanıt saymak</span>

Bir seçenek seçin.

**Soru 24 — Doğru cevap: c**

**Neden doğru:** Test tamamlama raporu, biten çalışmayı planla karşılaştırarak değerlendirir ve kalan risklerle çıkarılan dersleri bildirir. Böylece sponsorun geçmiş sapmalar, devam eden kalite sorunları ve gelecekteki iyileştirmeler hakkındaki bilgi ihtiyacını karşılar.

**En cazip yanlış (near-miss) — b:** Günlük hata bilgisi kaliteyle ilgili olduğu için caziptir. Ancak yeni hatalardaki günlük değişim, istenen sürüm düzeyindeki genel değerlendirmeyi tek başına sağlamaz.

**Diğer şıklar:** a) Sonraki dönemin planı, tamamlanmış sürümün testlerini ve plandan sapmalarını değerlendirmez. · d) Koşum takvimi yapılacak işin planıdır. Biten testlerin sonuçlarını ve kalan riskleri özetleyen kanıt değildir.

*Kaçırdıysanız tekrar edin: Test gözetimi, kontrolü ve tamamlama | Tuzak: Near-miss karışıklığı | LO: FL-5.3.2 (K2)*

[Kılavuzda tekrar edin: Test gözetimi, kontrolü ve tamamlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-3-2)



**Soru 25** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>The team uses coverage-based prioritization: rank each test by the total number of requirements it covers, with the largest total first. Coverage already provided by an earlier test does not reduce a later test's ranking. All four tests are executable and have equal duration.</p>
<div class="table-wrap"><table>
<thead>
<tr>
<th>Test</th>
<th>Requirements covered</th>
</tr>
</thead>
<tbody>
<tr>
<td>TC-L</td>
<td>R1, R2, R3, R4, R5</td>
</tr>
<tr>
<td>TC-M</td>
<td>R1, R2, R3, R4</td>
</tr>
<tr>
<td>TC-N</td>
<td>R4, R5, R6</td>
</tr>
<tr>
<td>TC-P</td>
<td>R5, R6</td>
</tr>
</tbody>
</table></div>
<p>Which execution order follows this rule?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Ekip kapsama dayalı önceliklendirme kullanır: her testi kapsadığı **toplam** gereksinim sayısına göre, en yüksek toplam önce gelecek biçimde sıralar. Önceki bir testin sağladığı kapsam, sonraki testin sırasını düşürmez. Dört testin hepsi koşulabilir ve süreleri eşittir.

| Test | Kapsanan gereksinimler |
|---|---|
| TC-L | R1, R2, R3, R4, R5 |
| TC-M | R1, R2, R3, R4 |
| TC-N | R4, R5, R6 |
| TC-P | R5, R6 |

Hangi koşum sırası bu kurala uyar?

</div>

a) <span lang="en">TC-L, TC-M, TC-N, TC-P</span><br><span lang="tr">TC-L, TC-M, TC-N, TC-P</span>

b) <span lang="en">TC-L, TC-N, TC-M, TC-P</span><br><span lang="tr">TC-L, TC-N, TC-M, TC-P</span>

c) <span lang="en">TC-N, TC-L, TC-M, TC-P</span><br><span lang="tr">TC-N, TC-L, TC-M, TC-P</span>

d) <span lang="en">TC-P, TC-N, TC-M, TC-L</span><br><span lang="tr">TC-P, TC-N, TC-M, TC-L</span>

Bir seçenek seçin.

**Soru 25 — Doğru cevap: a**

**Neden doğru:** Adım adım: 1. Her testin toplam gereksinim sayısını sayın: L = 5, M = 4, N = 3, P = 2. 2. Bu sayıları azalan sıraya koyun. 3. TC-L, TC-M, TC-N, TC-P sırasını elde edin. L, M’nin gereksinimlerini kapsasa bile kök ek kapsamı değil toplam kapsamı esas aldığı için M ikinci kalır.

**En cazip yanlış (near-miss) — b:** L’den sonra N, daha önce kapsanmamış R6’yı getirdiği için caziptir. Bu seçim ek kapsamı kullanır. Oysa verilen kural her testi toplam kapsamına göre sıralar; M’nin dört gereksinimi N’nin üçünden önce gelir.

**Diğer şıklar:** c) N üç gereksinim kapsar; toplam kapsam kuralında beş gereksinimli L’nin önüne geçemez. · d) Toplamları küçükten büyüğe sıralar. İstenen yüksek kapsamın önce gelmesi kuralını tersine çevirir.

*Kaçırdıysanız tekrar edin: Test planlama | Tuzak: Prosedür hatası | LO: FL-5.1.5 (K3)*

[Kılavuzda tekrar edin: Test planlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-1-5)



**Soru 26** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A retrospective identifies slow feedback from a shared test environment. The team tries reserved access slots in the next iteration and compares the waiting time with the earlier results. Why is this useful for testing?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Geçmişe dönük öğeler çalışmasında, ortak test ortamının geri bildirimi geciktirdiği belirlenir. Ekip sonraki döngüde ayrılmış erişim zamanları dener ve bekleme süresini önceki sonuçlarla karşılaştırır. Bunun test açısından yararı nedir?

</div>

a) <span lang="en">It transfers responsibility for testing from the team to the environment administrator</span><br><span lang="tr">Test sorumluluğunu ekipten ortam yöneticisine devreder.</span>

b) <span lang="en">It makes the retrospective result an exit criterion for the current test level</span><br><span lang="tr">Geçmişe dönük çalışmanın sonucunu mevcut test seviyesinin çıkış kriteri yapar.</span>

c) <span lang="en">It demonstrates that later iterations can omit test monitoring once the slots are assigned</span><br><span lang="tr">Zamanlar ayrılınca sonraki döngülerde test gözetiminin atlanabileceğini gösterir.</span>

d) <span lang="en">It turns reflection into an evaluated process change that can improve testing efficiency</span><br><span lang="tr">Değerlendirmeyi, etkisi ölçülen ve test verimliliğini artırabilecek değişime çevirmek</span>

Bir seçenek seçin.

**Soru 26 — Doğru cevap: d**

**Neden doğru:** Ekip bir iyileştirme uygular ve bekleme süresine etkisini değerlendirir. Böylece geçmişe dönük öğelerden (retrospectives) çıkan öğrenme, test sürecini iyileştirmeye yönelik somut ve değerlendirilebilir bir değişikliğe dönüşür.

**En cazip yanlış (near-miss) — b:** İyileştirme eylemi bir tamamlanma koşulu gibi görünebilir. Ancak bir eylemin kararlaştırılması onu kendiliğinden test seviyesinin çıkış kriteri yapmaz; kök süreç verimliliğinin iyileştirilmesini anlatır.

**Diğer şıklar:** a) Ortamın tahsis edilmesi ekibin test sorumluluğunu ortam yöneticisine devretmez. · c) Değişikliğin etkisini değerlendirmek ve sonraki testleri yönetmek için gözetim yararlı olmaya devam eder.

*Kaçırdıysanız tekrar edin: Yaşam döngüsü bağlamında test | Tuzak: Kaynak bilgi eksiği | LO: FL-2.1.6 (K2)*

[Kılavuzda tekrar edin: Yaşam döngüsü bağlamında test](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-1-6)



**Soru 27** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A team has extensive white-box coverage of its implementation, but a required export function is absent. A manager says the coverage result proves that every required function exists. How should the tester respond?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir ekip uygulamasında yüksek beyaz kutu kapsamı sağlamıştır; ancak gerekli bir dışa aktarma fonksiyonu eksiktir. Yönetici, kapsam sonucunun gerekli her fonksiyonun bulunduğunu kanıtladığını söyler. Test uzmanı nasıl yanıt vermelidir?

</div>

a) <span lang="en">Coverage of implemented structure may miss omitted functionality, so compare the product with its requirements</span><br><span lang="tr">Uygulanmış yapının kapsamı eksik fonksiyonları gözden kaçırabilir; ürünü gereksinimlerle karşılaştırın.</span>

b) <span lang="en">Coverage of implemented structure proves completeness, so close the missing-function report</span><br><span lang="tr">Uygulanmış yapının kapsamı eksiksizliği kanıtlar; eksik fonksiyon raporunu kapatın.</span>

c) <span lang="en">Coverage of implemented structure is subjective, so discard the coverage measurements</span><br><span lang="tr">Uygulanmış yapının kapsamı özneldir; kapsam ölçümlerini değerlendirme dışı bırakın.</span>

d) <span lang="en">Coverage of implemented structure requires complete requirements, so the export function must already exist</span><br><span lang="tr">Uygulanmış yapının kapsamı eksiksiz gereksinimler ister; dolayısıyla dışa aktarma zaten bulunmalıdır.</span>

Bir seçenek seçin.

**Soru 27 — Doğru cevap: a**

**Neden doğru:** Beyaz kutu kapsamı mevcut uygulamanın yapısını ele alır. Eksik bir gereksinim bu ölçümle ortaya çıkmayabilir. Bu nedenle gereksinimlere dayalı kontroller de gerekir; yüksek yapısal kapsam gereksinimlerin tamamının uygulandığını kanıtlamaz.

**En cazip yanlış (near-miss) — b:** Yüksek kapsam bütün testlerin tamamlandığı izlenimini verebilir. Ancak mevcut kodun kapsanması, hiç yazılmamış gerekli bir fonksiyonun bulunduğunu göstermez.

**Diğer şıklar:** c) Yapısal kapsam nesnel biçimde ölçülebilir. Buradaki sınırlama ölçümün öznelliği değil, hangi öğeleri ölçtüğüdür. · d) Beyaz kutu teknikleri uygulamayı esas alabilir; eksiksiz gereksinimler ön koşul değildir. Kapsamdan fonksiyonun varlığı sonucu çıkmaz.

*Kaçırdıysanız tekrar edin: Beyaz kutu test teknikleri | Tuzak: Kaynak bilgi eksiği | LO: FL-4.3.3 (K2)*

[Kılavuzda tekrar edin: Beyaz kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-3-3)



**Soru 28** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A release risk log contains the following entries. Which entry describes a PRODUCT risk?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir sürümün risk kaydında aşağıdaki maddeler bulunur. Hangisi bir **ÜRÜN** riskini anlatır?

</div>

a) <span lang="en">Screen-reader users may be unable to identify and activate the checkout controls</span><br><span lang="tr">Ekran okuyucu kullanıcıları ödeme kontrollerini tanıyıp etkinleştiremeyebilir.</span>

b) <span lang="en">Two experienced testers may leave the project in the middle of system testing</span><br><span lang="tr">İki deneyimli test uzmanı sistem testinin ortasında projeden ayrılabilir.</span>

c) <span lang="en">The middleware supplier may deliver the licensed components late</span><br><span lang="tr">Ara katman tedarikçisi lisanslı bileşenleri geç teslim edebilir.</span>

d) <span lang="en">Scope creep may enlarge the backlog beyond the planned budget</span><br><span lang="tr">Kapsam kayması iş listesini planlanan bütçenin ötesine büyütebilir.</span>

Bir seçenek seçin.

**Soru 28 — Doğru cevap: a**

**Neden doğru:** Ekran okuyucuyla ödeme kontrollerini kullanamamak, teslim edilen ürünün erişilebilirliğiyle ilgili olası bir kalite problemidir. Ürün riskleri ürünün kalite özelliklerini tehdit eder. Proje riskleri ise kaynak, takvim ve yönetim hedefleriyle ilgilidir.

**En cazip yanlış (near-miss) — b:** Personel kaybı sonraki testleri etkileyebileceği için ürün riski gibi görünebilir. Ancak doğrudan tehdit edilen proje kaynağı ve takvimidir; bu nedenle proje riskidir.

**Diğer şıklar:** c) Tedarikçinin geç teslimi proje takvimini tehdit eder. Teslim edilen ürünün kalite kusurunu tarif etmez. · d) Bütçeyi aşan kapsam büyümesi, projenin kapsam ve maliyet hedeflerini tehdit eden bir proje riskidir.

*Kaçırdıysanız tekrar edin: Risk yönetimi | Tuzak: Kaynak bilgi eksiği | LO: FL-5.2.2 (K2)*

[Kılavuzda tekrar edin: Risk yönetimi](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-2-2)



**Soru 29** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A tester is preparing a defect report for a notification service. The requirement is: "A repeated request with the same request ID must return the original notification ID and must not create another notification." The environment is service v3.8, build 614, with an empty notification store. The tester recorded:</p>
<div class="table-wrap"><table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr>
<th>Step</th>
<th>Request</th>
<th>Response</th>
<th>Store afterwards</th>
</tr>
</thead>
<tbody>
<tr>
<td>1</td>
<td>Send request ID R-84, recipient user-7</td>
<td>Notification N-901</td>
<td>N-901</td>
</tr>
<tr>
<td>2</td>
<td>Repeat the same request unchanged</td>
<td>Notification N-902</td>
<td>N-901 and N-902</td>
</tr>
</tbody>
</table></div>
<p>Which report excerpt correctly states the reproduction and expected/actual results?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir test uzmanı bildirim servisi için hata raporu hazırlamaktadır. Gereksinim şöyledir: “Aynı istek kimliğiyle yinelenen istek ilk bildirim kimliğini döndürmeli ve başka bildirim oluşturmamalıdır.” Ortam servis v3.8, yapı (build) 614 ve boş bildirim deposudur. Şu kayıtlar alınmıştır:

| Adım | İstek | Yanıt | Sonrasında depo |
|---|---|---|---|
| 1 | R-84 istek kimliğini, user-7 alıcısıyla gönder | Bildirim N-901 | N-901 |
| 2 | Aynı isteği değiştirmeden yinele | Bildirim N-902 | N-901 ve N-902 |

Hangi rapor alıntısı yeniden üretim adımlarını, beklenen ve gerçekleşen sonuçları doğru belirtir?

</div>

a) <span lang="en">Send two requests with different IDs; expect one notification; actual result is N-901 and N-902</span><br><span lang="tr">Farklı kimlikli iki istek gönder; tek bildirim bekle; gerçekleşen sonuç N-901 ve N-902’dir.</span>

b) <span lang="en">Send R-84 once; expect N-901; actual result is N-901, so the first send fails</span><br><span lang="tr">R-84’ü bir kez gönder; N-901 bekle; gerçekleşen sonuç N-901 olduğundan ilk gönderim başarısızdır.</span>

c) <span lang="en">Repeat R-84 unchanged; expect N-902 to be created; actual result is N-901, so retry fails</span><br><span lang="tr">R-84’ü değiştirmeden yinele; N-902 oluşmasını bekle; gerçekleşen sonuç N-901 olduğundan yineleme başarısızdır.</span>

d) <span lang="en">Send R-84, then repeat it unchanged; expect N-901 again and one stored notification; actual is N-902 and two</span><br><span lang="tr">R-84’ü gönder, değiştirmeden yinele; yeniden N-901 ve depoda tek bildirim bekle; gerçekleşen N-902 ve iki kayıttır.</span>

Bir seçenek seçin.

**Soru 29 — Doğru cevap: d**

**Neden doğru:** Adım adım: 1. Servis sürümünü, yapıyı ve boş depo ön koşulunu kaydedin. 2. R-84’ü göndererek N-901’i alın. 3. Aynı isteği değiştirmeden yineleyin. 4. Gereksinime göre N-901’in dönmesini ve tek kaydın korunmasını bekleyin. 5. Bunun yerine N-902 ve iki kayıt gözlendiğini bildirin. Rapor, uygulamadaki nedeni varsaymadan kanıtlanan sapmayı tarif eder.

**En cazip yanlış (near-miss) — c:** Yineleme doğru eylem olduğu için caziptir. Ancak beklenen ve gerçekleşen sonuçları ters çevirir; ikinci bildirim oluşturulmasını gereksinimmiş gibi sunar.

**Diğer şıklar:** a) İstek kimliklerini değiştirmek, aynı kimlikle yineleme koşulunu yeniden üretmez. Verilen bulguya uygun adımlar değildir. · b) İlk gönderim gözlenen beklentiyi karşılar. Hatayı ortaya çıkaran adım ikinci gönderimdir; ilk adımı başarısız diye raporlamak yanlıştır.

*Kaçırdıysanız tekrar edin: Hata yönetimi | Tuzak: Prosedür hatası | LO: FL-5.5.1 (K3)*

[Kılavuzda tekrar edin: Hata yönetimi](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-5-1)



**Soru 30** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A tester derives tests from input partitions, then uses experience with earlier mobile applications to add interruption and duplicate-submission tests. How should the second activity relate to the partition tests?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir test uzmanı girdi paylarından testler türetir. Ardından önceki mobil uygulama deneyimiyle kesinti ve yinelenen gönderim testleri ekler. İkinci aktivitenin pay testleriyle ilişkisi nasıl olmalıdır?

</div>

a) <span lang="en">It establishes complete statement coverage without examining any implementation structure</span><br><span lang="tr">Uygulamanın yapısını incelemeden tam komut kapsamı sağlar.</span>

b) <span lang="en">It supersedes the partition tests because past failures provide a complete test basis</span><br><span lang="tr">Geçmiş arızalar eksiksiz test esası sağladığından pay testlerinin yerini alır.</span>

c) <span lang="en">It complements the partition tests and may expose defects those tests do not detect</span><br><span lang="tr">Pay testlerini tamamlar ve onların tespit etmediği hataları ortaya çıkarabilir.</span>

d) <span lang="en">It converts the partition tests into white-box tests because it uses technical experience</span><br><span lang="tr">Teknik tecrübe kullandığından pay testlerini beyaz kutu testlerine dönüştürür.</span>

Bir seçenek seçin.

**Soru 30 — Doğru cevap: c**

**Neden doğru:** Hata tahminleme, insan hataları, yazılım hataları ve arızalar hakkındaki bilgiden yararlanarak testler ekler. Sistematik teknikleri tamamlar; bu tekniklerle bulunmayan hataları tespit edebilir. Geçmiş deneyim kullanılması pay testlerini gereksiz kılmaz.

**En cazip yanlış (near-miss) — b:** Geçmiş arızalara ilişkin bilgi yararlı olduğu için caziptir. Ancak bu bilginin yararlı olması, eksiksiz bir test esası sağladığını veya sistematik testlerin yerini aldığını göstermez.

**Diğer şıklar:** a) Komut kapsamı mevcut çalıştırılabilir komutlarla ilgilidir. Kök, yapısal öğelerin tamamının kapsandığına dair kanıt sağlamaz. · d) Teknik deneyim kullanılması test esasını kodun iç yapısına dönüştürmez; tekniklerin kategorileri bu nedenle değişmez.

*Kaçırdıysanız tekrar edin: Tecrübeye dayalı test teknikleri | Tuzak: Kaynak bilgi eksiği | LO: FL-4.4.1 (K2)*

[Kılavuzda tekrar edin: Tecrübeye dayalı test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-4-1)


### S31–S40



**Soru 31** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>To test a fee calculation, a tester reads the requirements document, splits the input ranges into partitions and selects representative values from each. The tester never looks at the code and does not draw on personal hunches. Which category of test techniques is being applied?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir test uzmanı ücret hesabını sınamak için gereksinim belgesini okur, girdi aralıklarını denklik paylarına ayırır ve her paydan temsilci değerler seçer. Koda bakmaz ve kişisel sezgilerinden yararlanmaz. Hangi test tekniği kategorisini uygular?

</div>

a) <span lang="en">Experience-based test techniques</span><br><span lang="tr">Tecrübeye dayalı test teknikleri</span>

b) <span lang="en">Black-box test techniques</span><br><span lang="tr">Kara kutu test teknikleri</span>

c) <span lang="en">White-box test techniques</span><br><span lang="tr">Beyaz kutu test teknikleri</span>

d) <span lang="en">Non-functional test types</span><br><span lang="tr">Fonksiyonel olmayan test çeşitleri</span>

Bir seçenek seçin.

**Soru 31 — Doğru cevap: b**

**Neden doğru:** Testler belgelenmiş gereksinimlerdeki girdi aralıklarından türetilir. Denklik paylarına ayırma, belirtime dayalı bir kara kutu test tekniğidir. Değer seçerken muhakeme kullanılması tekniğin esasını değiştirmez.

**En cazip yanlış (near-miss) — a:** Temsilci değer seçmek kişisel yargıya benzetilebildiği için caziptir. Ancak burada seçimi belgelenmiş paylar yönlendirir. Sezgi ve geçmiş arıza bilgisi testlerin esası olarak kullanılmamıştır.

**Diğer şıklar:** c) Beyaz kutu teknikleri iç yapıyı esas alır. Senaryoda koda bakılmadığı açıkça belirtilmiştir. · d) Bu bir test çeşidi sınıflandırmasıdır; sorulan teknik kategorisi değildir. Ayrıca ücret hesabı fonksiyonel bir davranıştır.

*Kaçırdıysanız tekrar edin: Test tekniklerine genel bakış | Tuzak: Near-miss karışıklığı | LO: FL-4.1.1 (K2)*

[Kılavuzda tekrar edin: Test tekniklerine genel bakış](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-1-1)



**Soru 32** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Working under heavy deadline pressure and without training in the new framework, a developer writes an incorrect API call in the payment module. Weeks later, customer payments start to crash. What is the ROOT CAUSE in this scenario?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Yoğun teslim tarihi baskısı altında çalışan ve yeni yazılım çatısı konusunda eğitim almamış bir geliştirici, ödeme modülüne yanlış bir API çağrısı yazar. Haftalar sonra müşterilerin ödeme işlemleri çökmeye başlar. Bu senaryodaki **KÖK NEDEN** nedir?

</div>

a) <span lang="en">The incorrect API call in the payment module</span><br><span lang="tr">Ödeme modülündeki yanlış API çağrısı</span>

b) <span lang="en">The haste and inexperience that caused the mistake</span><br><span lang="tr">İnsan hatasına yol açan acele ve deneyimsizlik</span>

c) <span lang="en">The crash that the paying customers experienced</span><br><span lang="tr">Ödeme yapan müşterilerin yaşadığı çökme</span>

d) <span lang="en">The absence of an automated regression test for the payment module</span><br><span lang="tr">Ödeme modülü için otomatik regresyon testinin bulunmaması</span>

Bir seçenek seçin.

**Soru 32 — Doğru cevap: b**

**Neden doğru:** Kök neden, bir problemin oluşmasının temelindeki gerekçedir. Burada teslim tarihi baskısı ve eğitim eksikliği geliştiricinin insan hatasını yapmasına zemin hazırlamıştır. Bu koşulları iyileştirmek benzer problemlerin oluşma olasılığını azaltabilir.

**En cazip yanlış (near-miss) — a:** Düzeltilmesi gereken somut öğe yanlış API çağrısı olduğundan caziptir. Ancak çağrı yazılımdaki hatadır (defect). Soru bu hataya yol açan koşulların temelindeki kök nedeni sorar.

**Diğer şıklar:** c) Çökme, müşterinin gözlemlediği arızadır (failure). Problemin ortaya çıkan sonucudur. · d) Eksik regresyon testi, hatayı tespit etme fırsatının kaçırılmasıyla ilgilidir. Senaryoda insan hatasına yol açan koşulları açıklamaz.

*Kaçırdıysanız tekrar edin: Test neden gereklidir? | Tuzak: Near-miss karışıklığı | LO: FL-1.2.3 (K2)*

[Kılavuzda tekrar edin: Test neden gereklidir?](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-2-3)



**Soru 33** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A team has budgeted for earlier test activities, but the business stakeholders still consider testing a final handover and decline to support the change. Which condition for adopting shift left needs attention?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir ekip erken test aktiviteleri için bütçe ayırmıştır. Ancak iş paydaşları testi hâlâ son teslim aşaması olarak görür ve değişikliği desteklemez. Sola alma (shift left) yaklaşımını benimsemek için hangi koşula dikkat edilmelidir?

</div>

a) <span lang="en">Convince stakeholders of the approach and obtain their support for earlier testing</span><br><span lang="tr">Paydaşları yaklaşıma ikna etmek ve erken test için desteklerini almak</span>

b) <span lang="en">Move the early activities back to final handover and call the result shift left</span><br><span lang="tr">Erken aktiviteleri son teslim aşamasına geri taşıyıp sonucu sola alma diye adlandırmak</span>

c) <span lang="en">Remove the need for stakeholders to support earlier testing by increasing the automation budget</span><br><span lang="tr">Otomasyon bütçesini artırarak erken test için paydaş desteği gereksinimini kaldırmak</span>

d) <span lang="en">Delay discussion of the approach until system testing has already been completed</span><br><span lang="tr">Yaklaşımın görüşülmesini sistem testi tamamlanana kadar ertelemek</span>

Bir seçenek seçin.

**Soru 33 — Doğru cevap: a**

**Neden doğru:** Sola alma, test aktivitelerini yaşam döngüsünün daha erken aşamalarına taşır. TTB ders programında shift-left olarak da geçen bu yaklaşımın benimsenmesi, paydaşların yaklaşımı anlamasını ve desteklemesini gerektirir. Bütçe ayırmak tek başına bu desteği sağlamaz.

**En cazip yanlış (near-miss) — c:** Otomasyon bazı erken test aktivitelerini destekleyebildiği için caziptir. Ancak araçlara daha fazla bütçe ayırmak, süreç değişikliği için iş paydaşlarının desteğinin yerine geçmez.

**Diğer şıklar:** b) Aktiviteleri son teslim aşamasına geri taşımak, testi daha erkene alma yaklaşımını uygulamaz. · d) Sistem testinin bitmesini beklemek, erken testin önündeki mevcut destek sorununu çözmez.

*Kaçırdıysanız tekrar edin: Yaşam döngüsü bağlamında test | Tuzak: Kaynak bilgi eksiği | LO: FL-2.1.5 (K2)*

[Kılavuzda tekrar edin: Yaşam döngüsü bağlamında test](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-1-5)



**Soru 34** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Static analysis flags unreachable code and a requirement review finds an ambiguous response-time limit. The team then runs concurrent requests and observes unacceptable response times. Which comparison is accurate?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Statik analiz erişilemeyen kodu işaretler; bir gereksinim gözden geçirmesi belirsiz bir yanıt süresi sınırı bulur. Ekip daha sonra eşzamanlı istekler koşar ve kabul edilemez yanıt süreleri gözlemler. Hangi karşılaştırma doğrudur?

</div>

a) <span lang="en">Static testing detects issues in work products directly; dynamic testing observes failures during execution</span><br><span lang="tr">Statik test iş ürünlerindeki sorunları doğrudan tespit eder; dinamik test koşum sırasında arızaları gözlemler.</span>

b) <span lang="en">Static testing observes failures during execution; dynamic testing detects issues in work products directly</span><br><span lang="tr">Statik test koşum sırasında arızaları gözlemler; dinamik test iş ürünlerindeki sorunları doğrudan tespit eder.</span>

c) <span lang="en">Static testing and dynamic testing provide the same evidence because each reported item concerns a defect</span><br><span lang="tr">Bildirilen her öğe bir hatayla ilgili olduğundan statik ve dinamik test aynı kanıtı sağlar.</span>

d) <span lang="en">Static testing measures actual response times; dynamic testing determines whether the requirement is ambiguous</span><br><span lang="tr">Statik test gerçekleşen yanıt sürelerini ölçer; dinamik test gereksinimin belirsiz olup olmadığını belirler.</span>

Bir seçenek seçin.

**Soru 34 — Doğru cevap: a**

**Neden doğru:** Statik test, test nesnesini çalıştırmadan iş ürünlerini inceler. Erişilemeyen kod veya belirsiz gereksinim bu yolla bulunabilir. Dinamik test çalıştırılan yazılımın davranışını gözlemler; kabul edilemez yanıt süreleri gibi arızaları ortaya çıkarabilir.

**En cazip yanlış (near-miss) — c:** Her iki çalışma da kalite sorunlarını bulabildiği için caziptir. Ancak sağladıkları gözlemler farklıdır: biri iş ürününün doğrudan incelenmesi, diğeri çalışan yazılımın davranışıdır.

**Diğer şıklar:** b) Statik ve dinamik testin tespit biçimlerini tersine çevirir. Koşum sırasındaki arızalar dinamik testte gözlemlenir. · d) Gerçekleşen yanıt süresini ölçmek koşum gerektirir. Gereksinimin belirsizliği ise metin incelenerek bulunabilir.

*Kaçırdıysanız tekrar edin: Statik testin temelleri | Tuzak: Kaynak bilgi eksiği | LO: FL-3.1.3 (K2)*

[Kılavuzda tekrar edin: Statik testin temelleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-3.html#fl-3-1-3)



**Soru 35** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A tester counts the two outcomes of every conditional decision but leaves unconditional transfers out of the coverage inventory. The tester calls the result branch coverage. What correction is needed?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir test uzmanı her koşullu kararın iki sonucunu sayar, ancak koşulsuz aktarımları kapsam envanterinin dışında bırakır. Sonucu dal kapsamı olarak adlandırır. Hangi düzeltme gerekir?

</div>

a) <span lang="en">Use the requirements as coverage items instead of any transfers in the code</span><br><span lang="tr">Koddaki aktarımlar yerine gereksinimleri kapsam öğeleri olarak kullanmak</span>

b) <span lang="en">Use executable statements as the coverage items and keep the branch label</span><br><span lang="tr">Kapsam öğesi olarak çalıştırılabilir komutları kullanıp dal adını korumak</span>

c) <span lang="en">Exclude unconditional transfers because conditional outcomes define the complete branch inventory</span><br><span lang="tr">Koşullu sonuçlar bütün dal envanterini tanımladığından koşulsuz aktarımları dışlamak</span>

d) <span lang="en">Include unconditional and conditional branches in the branch coverage inventory</span><br><span lang="tr">Dal kapsamı envanterine hem koşulsuz hem koşullu dalları dahil etmek</span>

Bir seçenek seçin.

**Soru 35 — Doğru cevap: d**

**Neden doğru:** Dal testinin kapsam öğeleri dallardır. Bunlar koşullu kararların sonuçlarını ve koşulsuz aktarımları içerir. Yalnız koşullu sonuçları saymak dal envanterini eksik bırakır.

**En cazip yanlış (near-miss) — c:** Karar sonuçları gerçekten koşullu dallar olduğu için caziptir. Ancak dal kavramı onlarla sınırlı değildir; koşulsuz dalların da kapsam hesabına dahil edilmesi gerekir.

**Diğer şıklar:** a) Gereksinimleri kullanmak farklı bir kapsam ölçütünü ölçer. Dal envanterindeki eksikliği gidermez. · b) Çalıştırılabilir komutlar komut kapsamının öğeleridir. Bunları sayıp dal kapsamı adını korumak ölçütleri karıştırır.

*Kaçırdıysanız tekrar edin: Beyaz kutu test teknikleri | Tuzak: Near-miss karışıklığı | LO: FL-4.3.2 (K2)*

[Kılavuzda tekrar edin: Beyaz kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-3-2)



**Soru 36** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Before the official launch, a pre-release version of a banking app is made available to a selected group of external customers, who use it at their own locations and report their experiences. Which form of testing is this?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir bankacılık uygulamasının yayım öncesi sürümü, resmî çıkıştan önce seçilmiş dış müşterilere sunulur. Müşteriler uygulamayı kendi yerlerinde kullanır ve deneyimlerini bildirir. Bu hangi test biçimidir?

</div>

a) <span lang="en">Alpha testing</span><br><span lang="tr">Alfa testi</span>

b) <span lang="en">Beta testing</span><br><span lang="tr">Beta testi</span>

c) <span lang="en">Operational acceptance testing</span><br><span lang="tr">Operasyonel kabul testi</span>

d) <span lang="en">System testing</span><br><span lang="tr">Sistem testi</span>

Bir seçenek seçin.

**Soru 36 — Doğru cevap: b**

**Neden doğru:** Beta testi, potansiyel veya mevcut kullanıcıların yayım öncesi sürümü kendi yerlerinde değerlendirdiği bir kabul testi biçimidir. Senaryoda seçilmiş dış müşterilerin kendi yerlerinde kullanımı bu bağlamı sağlar.

**En cazip yanlış (near-miss) — a:** Alfa testi de dış kullanıcıları ve yayım öncesi sürümü içerebildiği için caziptir. Ancak alfa testi geliştiren kuruluşun yerinde yapılır; kökte kullanıcıların kendi yerleri belirtilmiştir.

**Diğer şıklar:** c) Operasyonel kabul testi yedekleme, kurtarma ve bakım gibi işletime hazır olma konularını değerlendirir. Kök bu amacı anlatmaz. · d) Sistem testi bütün sistemin davranışını değerlendirir. Burada yayım öncesi kullanıcı kabulü ve kullanıcıların kendi yerleri beta testini belirler. Müşteri olmak tek başına sistem testine katılmayı dışlamaz.

*Kaçırdıysanız tekrar edin: Test seviyeleri ve test çeşitleri | Tuzak: Near-miss karışıklığı | LO: FL-2.2.1 (K2)*

[Kılavuzda tekrar edin: Test seviyeleri ve test çeşitleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-2-1)



**Soru 37** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A team uses a rule-oriented acceptance-criteria list for a discount story. A reviewer claims that the list cannot communicate the story's scope because it is not written as Given/When/Then scenarios. Which assessment is appropriate?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir ekip indirimle ilgili kullanıcı hikayesi için kural odaklı kabul kriterleri listesi kullanır. Bir gözden geçirici, liste Given/When/Then senaryolarıyla yazılmadığından hikayenin kapsamını aktaramayacağını söyler. Hangi değerlendirme uygundur?

</div>

a) <span lang="en">The claim is valid because a rule-oriented list is a test procedure rather than acceptance criteria</span><br><span lang="tr">İddia geçerlidir; kural odaklı liste kabul kriterleri değil, test prosedürüdür.</span>

b) <span lang="en">The claim is valid because checklist-based testing is the required acceptance-criteria format</span><br><span lang="tr">İddia geçerlidir; zorunlu kabul kriteri biçimi kontrol listesine dayalı testtir.</span>

c) <span lang="en">The claim is invalid because acceptance criteria must describe implementation structure</span><br><span lang="tr">İddia geçersizdir; kabul kriterleri uygulamanın iç yapısını anlatmak zorundadır.</span>

d) <span lang="en">The claim is invalid because rule-oriented criteria can also state the acceptance conditions</span><br><span lang="tr">İddia geçersizdir; kural odaklı kriterler de kabul koşullarını belirtebilir.</span>

Bir seçenek seçin.

**Soru 37 — Doğru cevap: d**

**Neden doğru:** Ders programı hem senaryo odaklı hem kural odaklı kabul kriteri biçimlerini içerir. Uygun bir kural listesi kabul koşullarını tanımlayabilir ve kapsamı netleştirebilir. Given/When/Then bütün hikayelere zorunlu tutulan bir biçim değildir.

**En cazip yanlış (near-miss) — a:** Bir liste işlem adımlarını andırabildiği için caziptir. Ancak kabul koşullarını sıralamak, testin nasıl koşulacağını adım adım tarif etmekle aynı değildir.

**Diğer şıklar:** b) Kontrol listesine dayalı test etme bir test tekniğidir. Kabul kriterlerinin zorunlu yazım biçimi değildir. · c) Kabul kriterleri kabul koşullarını tanımlar. Uygulamanın iç yapısını tarif etme zorunluluğu yoktur.

*Kaçırdıysanız tekrar edin: İş birliğine dayalı test yaklaşımları | Tuzak: Dikkatsiz okuma | LO: FL-4.5.2 (K2)*

[Kılavuzda tekrar edin: İş birliğine dayalı test yaklaşımları](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-5-2)



**Soru 38** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A pipeline tool builds the application after each merge, deploys it to a fresh test environment, triggers the automated suites in sequence and promotes the build when they pass. Its primary purpose is to orchestrate the delivery pipeline rather than implement the individual tests. Which tool category best matches that purpose?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir teslimat hattı aracı her birleştirmeden sonra uygulamayı derler, yeni test ortamına kurar, otomatik test takımlarını sırayla tetikler ve testler geçtiğinde yapıyı sonraki aşamaya geçirir. Temel amacı tek tek testleri oluşturmak değil, teslimat hattını düzenlemektir. Hangi araç kategorisi bu amaca **EN İYİ** uyar?

</div>

a) <span lang="en">A tool for test design and test implementation in the delivery process</span><br><span lang="tr">Teslimat sürecinde test tasarımı ve test uyarlama aracı</span>

b) <span lang="en">A static testing tool for analyzing the source code</span><br><span lang="tr">Kaynak kodunu analiz eden statik test aracı</span>

c) <span lang="en">A DevOps tool supporting continuous integration and delivery</span><br><span lang="tr">Sürekli entegrasyon ve teslimatı destekleyen DevOps aracı</span>

d) <span lang="en">A tool for managing the test process and its testware</span><br><span lang="tr">Test sürecini ve test çalışma ürünlerini yöneten araç</span>

Bir seçenek seçin.

**Soru 38 — Doğru cevap: c**

**Neden doğru:** Uygulamayı derleme, ortama kurma, test aşamalarını tetikleme ve geçen yapıları ilerletme, teslimat akışının düzenlenmesidir. Sürekli entegrasyon ve sürekli teslimatı destekleyen bu amaç DevOps araçlarıyla örtüşür.

**En cazip yanlış (near-miss) — d:** Hangi işin ne zaman koşacağını düzenlemek test yönetimine benzediği için caziptir. Ancak test yönetimi araçları plan, ilerleme ve test çalışma ürünlerini yönetir; buradaki aracın temel işi teslimat akışını otomatikleştirmektir.

**Diğer şıklar:** a) Bu araçlar test senaryosu ve verisi oluşturmayı destekler. Kökteki araç mevcut testleri teslimat akışında çalıştırır. · b) Statik test araçları iş ürünlerinin incelenmesini destekler. Kökteki derleme, kurulum ve koşum akışını en iyi açıklayan kategori değildir.

*Kaçırdıysanız tekrar edin: Test için araç desteği | Tuzak: Near-miss karışıklığı | LO: FL-6.1.1 (K2)*

[Kılavuzda tekrar edin: Test için araç desteği](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-6.html#fl-6-1-1)



**Soru 39** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>Test design has just finished for the payment feature. Which work products has this activity produced?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Ödeme özelliğinin test tasarımı yeni tamamlanmıştır. Bu aktivite hangi iş ürünlerini üretmiştir?

</div>

a) <span lang="en">Test cases and test data requirements</span><br><span lang="tr">Test senaryoları ve test verisi gereksinimleri</span>

b) <span lang="en">Test procedures and automated test scripts</span><br><span lang="tr">Test prosedürleri ve otomatik test betikleri</span>

c) <span lang="en">Test conditions and the prioritized test basis</span><br><span lang="tr">Test koşulları ve önceliklendirilmiş test esası</span>

d) <span lang="en">Test logs and test progress reports</span><br><span lang="tr">Test kayıtları ve test ilerleme raporları</span>

Bir seçenek seçin.

**Soru 39 — Doğru cevap: a**

**Neden doğru:** Test tasarımı test senaryolarını (test cases) ve bu senaryoların gerektirdiği test verisi gereksinimlerini oluşturur. Test koşullarından, davranışın nasıl sınanacağına ilişkin daha somut tasarıma geçilir. Aktiviteler örtüşebilir ve tekrarlanabilir; soru karakteristik çıktıları sorar.

**En cazip yanlış (near-miss) — b:** Prosedürler ve betikler tasarımın doğal çıktıları gibi görünebilir. Ancak bunlar test uyarlamada, tasarlanmış senaryoları koşulabilir test çalışma ürünlerine dönüştürürken hazırlanır.

**Diğer şıklar:** c) Test koşulları tasarımdan önceki test analizinin çıktıları arasındadır. Bu çift test tasarımının karakteristik çıktısı değildir. · d) Test kayıtları koşumdan, test ilerleme raporları gözetim ve kontrolden gelir.

*Kaçırdıysanız tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller | Tuzak: Near-miss karışıklığı | LO: FL-1.4.3 (K2)*

[Kılavuzda tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-4-3)



**Soru 40** (1 puan)

<div class="bilingual en" lang="en"><strong>EN</strong>
<p>A developer exhaustively tests a tiny function with two Boolean inputs by checking all four input combinations. A manager says this disproves the principle that exhaustive testing is impossible. Which assessment is correct?</p>
</div>

<div class="bilingual tr" lang="tr"><strong>TR</strong>

Bir geliştirici, iki Boole girdili çok küçük bir fonksiyonun dört girdi birleşiminin tamamını kontrol ederek kapsamlı test yapar. Bir yönetici bunun “Yazılımı %100 test etmek imkansızdır” ilkesini çürüttüğünü söyler. Hangi değerlendirme doğrudur?

</div>

a) <span lang="en">The principle is disproved because a finite input space makes exhaustive testing practical for any product</span><br><span lang="tr">Sonlu girdi uzayı her ürünün tümüyle test edilmesini uygulanabilir kıldığı için ilke çürütülmüştür.</span>

b) <span lang="en">The manager is correct because exhaustive input testing proves the entire product is defect-free</span><br><span lang="tr">Girdilerin tümünü test etmek bütün ürünün hatasızlığını kanıtladığı için yönetici haklıdır.</span>

c) <span lang="en">The example is compatible with the principle, which allows exhaustive testing in trivial cases</span><br><span lang="tr">Örnek, çok basit durumlarda tüm olasılıkların testine izin veren ilkeyle uyumludur.</span>

d) <span lang="en">The example is invalid because exhaustive testing must include production traffic</span><br><span lang="tr">Tüm olasılıkların testi üretim trafiğini de içermek zorunda olduğundan örnek geçersizdir.</span>

Bir seçenek seçin.

**Soru 40 — Doğru cevap: c**

**Neden doğru:** İlke, çok basit durumları istisna olarak tanır. Dört birleşimli küçük bir fonksiyonun girdi uzayını bütünüyle sınamak, karmaşık ürünlerde bütün olasılıkların testini uygulanabilir hâle getirmez. Sınırlı örnek genel ilkeyle uyumludur.

**En cazip yanlış (near-miss) — a:** Girdi uzayı gerçekten sonlu olduğu için caziptir. Ancak sonlu bir uzay da test edilemeyecek kadar büyük olabilir. Sonlu olmak, uygulanabilir olmakla aynı değildir.

**Diğer şıklar:** b) Küçük bir fonksiyondaki girdileri kontrol etmek, bütün ürünün hatasız olduğunu kanıtlamaz. · d) Üretim trafiği, bütün olasılıkları test etmenin her durumda geçerli bir koşulu değildir.

*Kaçırdıysanız tekrar edin: Test prensipleri | Tuzak: Near-miss karışıklığı | LO: FL-1.3.1 (K2)*

[Kılavuzda tekrar edin: Test prensipleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-3-1)


## Sınav günü kontrol listesi

- Sağlayıcınızın güncel sınav dilini, süreyi ve varsa ek süre hakkınızı kontrol edin.
- Kimlik ve teknik hazırlık koşullarını, bağlantı ve kamera gereksinimlerini tamamlayın.
- Başlamadan önce soru ve puanlama talimatlarını okuyun.
- Tek seçimli ve varsa çok seçimli sorularda istenen seçenek sayısına dikkat edin; bu denemede bir soru iki seçimlidir.
- Uzayan soruyu işaretleyip süre izin veriyorsa geri dönün.
- Teslimden önce boş soruları ve işaretlediğiniz cevapları kontrol edin.

## Kaynakça

- ISTQB®, *Certified Tester Foundation Level Syllabus v4.0.1*, 15 Eylül 2024. Telif: ISTQB ve belgede belirtilen yazarlar. [Resmî CTFL sayfası](https://www.istqb.org/certifications/certified-tester-foundation-level-ctfl-v4-0/).
- ISTQB®, *Exam Structure Tables v1.18*, 27 Mayıs 2026; CTFL v4.0 tablosu. [ISTQB sınav belgeleri](https://www.istqb.org/).
- ISTQB®, *Exam Structures and Rules v1.2*, 2 Mayıs 2025. [ISTQB](https://www.istqb.org/).
- TTB, *Temel Seviye Ders Programı v4.0.1* Türkçe çevirisi ve *Yazılım Testi Terimler Sözlüğü v2*. [TTB hazırlık belgeleri](https://www.turkishtestingboard.org/foundation-level/).
- Kadir Çamoğlu, *ISTQB® CTFL® v4.0 Sınav Rehberi: Sıfırdan Sınava Hazır Seviyeye*, Türkçe kılavuz. [Türkçe kılavuz](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/).

CTFL v4.0.1 ders programı yazarları: Renzo Cerquozzi, Wim Decoutere, Jean-François Riverin, Arnika Hryszko, Martin Klonk, Meile Posthuma, Eric Riou du Cosquer, Adam Roman, Lucjan Stapp, Stephanie Ulrich ve Eshraka Zakaria. v4.0 yazarları ayrıca Klaudia Dussa-Zieger, Michaël Pilaeten ve Stuart Reid'i içerir. Ders programı ve bu belgeden kullanılan kavram adları ISTQB'nin hakları saklı materyalidir.

Sürüm: 19 Ekim 2026 · Geri bildirim: [kadir.camoglu@gmail.com](mailto:kadir.camoglu@gmail.com).

