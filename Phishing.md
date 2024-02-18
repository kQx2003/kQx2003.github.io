What is a phishing attack?
“Phishing” refers to an attempt to steal sensitive information, typically in the form of usernames, passwords, credit card numbers, bank account information or other important data in order to utilize or sell the stolen information. By masquerading as a reputable source with an enticing request, an attacker lures in the victim in order to trick them, similarly to how a fisherman uses bait to catch a fish.

<img src="https://www.cloudflare.com/img/learning/security/threats/phishing-attack/diagram-phishing-attack.png">

How is phishing carried out?
The most common examples of phishing are used to support other malicious actions, such as on-path attack and cross-site scripting attacks. These attacks typically occur via email or instant message, and can be broken down into a few general categories. It’s useful to become familiar with a few of these different vectors of phishing attacks in order to spot them in the wild.
Advanced-fee scam
This common email phishing attack is popularized by the “Nigerian prince” email, where an alleged Nigerian prince in a desperate situation offers to give the victim a large sum of money for a small fee upfront. Unsurprisingly, when the fee is paid, no large sum of money ever arrives. The interesting history is that this type of scam has been occurring for over a hundred years in different forms; it was originally known in the late 1800s as the Spanish Prisoner scam, in which a con artist contacted a victim to prey on their greed and sympathy. The con artist is allegedly trying to smuggle out a wealthy Spanish prisoner, who will reward the victim handsomely in exchange for the money to bribe some prison guards.

This attack (in all its forms) is mitigated by not responding to requests from unknown parties in which money has to be given to receive something in return. If it sounds too good to be true, it probably is. A simple Google search on the theme of the request or some of the text itself will often bring up the details of the scam.

Account deactivation scam
By playing off the urgency created in a victim who believes an important account is going to be deactivated, attackers are able to trick some people into handing over important information such as login credentials. Here’s an example: the attacker sends an email that appears to come from an important institution like a bank, and they claim the victim’s bank account will be deactivated if they do not take action quickly. The attacker will then request the login and password to the victim’s bank account in order to prevent the deactivation. In a clever version of the attack, once the information is entered, the victim will be directed to the legitimate bank website so that nothing looks out of place.

This type of attack can be countered by going directly to the website of the service in question and seeing if the legitimate provider notifies the user of the same urgent account status. It’s also good to check the URL bar and make sure that the website is secure. Any website requesting a login and password that is not secure should be seriously questioned, and nearly without exception should not be used.

Website forgery scam
This type of scam is commonly paired with other scams such as the account deactivation scam. In this attack, the attacker creates a website that is virtually identical to the legitimate website of a business the victim uses, such as a bank. When the user visits the page through whatever means, be it an email phishing attempt, a hyperlink inside a forum, or via a search engine, the victim reaches a website which they believe to be the legitimate site instead of a fraudulent copy. All information entered by the victim is collected for sale or other malicious use.

In the early days of the Internet, these types of duplicate pages were fairly easy to spot due to their shoddy craftsmanship. Today the fraudulent sites may look like a picture-perfect representation of the original. By checking the URL in the web browser, it is usually pretty easy to spot a fraud. If the URL looks different than the typical one, this should be considered highly suspect. If the pages listed as insecure and HTTPS is not on, this is a red flag and virtually guarantees the site is either broken or a phishing attack.

What is spear phishing?
This type of phishing is directed at specific individuals or companies, hence the term spear phishing. By gathering details or buying information about a particular target, an attacker is able to mount a personalized scam. This is currently the most effective type of phishing, and accounts for over 90% of the attacks.

What is clone phishing?
Clone phishing involves mimicking a previously delivered legitimite email and modifying its links or attached files in order to trick the victim into opening a malicious website or file. For example, by taking an email and attaching a malicious file with the same filename as the original attached file, and then resending the email with a spoofed email address that appears to come from the original sender, attackers are able to exploit the trust of the initial communication in order to get the victim to take action.

What is whaling?
For attacks that are directed specifically at senior executives or other privileged users within businesses, the term whaling is commonly used. These type of attacks are typically targeted with content likely to require the attention of the victim such as legal subpoenas or other executive issues.

Another common vector of this style of attack is whaling scam emails that appear to come from an executive. A common example would be an email request coming from a CEO to someone in the finance department requesting their immediate help in transferring money. Lower-level employees are sometimes fooled into thinking the importance of the request and the person it’s coming from supersede any need to double check the request’s authenticity, resulting in the employee transferring large sums of money to an attacker.

How does Cloudflare help organizations defend against phishing attacks?
Phishing can occur over a variety of attack vectors, but one of the biggest is email. Many email providers automatically try to block phishing emails, but sometimes they still get through to users, making email security an important concern.

Cloudflare Area 1 Email Security offers advanced phishing protection, crawling the Internet and investigating phishing infrastructure to identify phishing campaigns in advance. Learn how Cloudflare Area 1 works.

Phishing คืออะไร ทำไมถึงผู้ใช้งานอินเทอร์เน็ตถึงต้องรู้จัก
<img src="https://www.quickserv.co.th/texteditor/uploade/1177.jpg">

อินเทอร์เน็ตกับการใช้งานคอมพิวเตอร์ในยุคปัจจุบันนี้ เราแทบจะเรียกได้เลยว่าทั้งสองอย่างนั้นเป็นของคู่กันที่แยกจากกันแทบไม่ได้ ไม่ว่าจะเป็นการใช้คอมพิวเตอร์เพื่อการทำงาน โดยเฉพาะอย่างยิ่งกับเรื่องบันเทิงและเกม อย่างจะเห็นว่าอินเทอร์เน็ตกลายเป็นสิ่งที่เข้ามามีบทบาทสำคัญกับการใช้ชีวิตของเราเป็นอย่างมากที่สุด และเมื่อเป็นเรื่องดี ๆ มีประโยชน์ก็เป็นธรรมดาที่จะมีเรื่องอันตรายที่น่าเป็นห่วงอยู่ในนั้นด้วยเสมอ และ phishing คือหนึ่งในเรื่องอันตรายเหล่านั้น

เรียนรู้ว่า Phishing คืออะไร

phishing คือรูปแบบของการหลอกลวงผ่านช่องทางการใช้งานอินเทอร์เน็ตของผู้ใช้ทั่วไป ซึ่งไม่ใช่การล่อลวงธรรมดาที่เราพบเห็นกันทั่วไป แต่จะเป็นกลยุทธ์การหลอกที่ใช้วิธีทางจิตวิทยาเข้าร่วมด้วย ส่วนใหญ่แล้วจะมาในรูปแบบของอีเมล์ เว็บไซต์ และสื่อสังคมออนไลน์ในรูปแบบต่าง ๆ ที่จะทำการหลอกให้ผู้ใช้กรอกข้อมูลส่วนบุคคลที่เป็นความลับ ไม่ว่าจะเป็นรหัสผ่าน หมายเลขบัตรประชาชน เลขที่ Passport รวมไปถึงข้อมูลลับทางการเงิน ทั้งเลขที่บัญชีและรหัสผ่าน หรือจะเป็นการหลอกให้กดยอมรับและติดตั้งไวรัสตัวร้ายเข้าสู่คอมพิวเตอร์ของตัวเอง

หากใครได้มานั่งอ่านเรื่องที่บอกว่า phishing คือวายร้ายอย่างนี้ ต่างก็จะบอกเหมือนกันว่าเราคงไม่มีทางยอมให้หลอกง่าย ๆ เด็ดขาด แต่อย่างที่บอกไปว่า การ phishing เป็นการหลอกลวงที่มีศิลปะทำให้เราหลงเชื่อได้ง่ายกว่า โดยส่วนใหญ่จะมาในรูปของอีเมล์แจ้งเตือน ทั้งจากธนาคาร เว็บ Social ที่เราใช้งานกันเป็นประจำอย่าง Facebook, Twitter ที่พอผู้ใช้หลายคนได้เห็นหัวข้อความก็จะเกิดความเชื่อว่าปลอดภัยและยอมทำตามโดยง่าย โดยทั่วไปจะนิยมให้กดที่ Link เพื่อย้ายไปยังหน้าเว็บอื่นเพื่อทำการกรอกข้อมูล แน่นอนว่าเว็บที่ Link พาไปก็จะทำเลียนแบบจนเกือบจะเหมือนกับต้นฉบับเลย

Phishing คือการล่อลวงที่มีรูปแบบที่แตกต่าง

หลังจากที่เราสามารถสรุปได้แล้วว่า phishing คือรูปแบบการหลอกลวงทางอินเทอร์เน็ตที่หากได้ลองพลาดแล้วก็ต้องมานั่งปวดหัวกันยาวเลยทีเดียว ซึ่งหากเราจะลองแบ่งประเภทของ phishing ดูแล้ว ก็จะแบ่งได้เป็น 2 ประเภท โดยจะเป็นแบบธรรมดาและแบบเจาะจง ซึ่งมีความแตกต่างกันตรงที่เรื่องของการระบุเป้าหมาย ซึ่ง phishing แบบธรรมดาจาเป็นการหว่านอีเมล์หรือ Link ไปเรื่อย เผื่อว่าจะโดนใครสักคนหนึ่งและก็จะได้ข้อมูลไปใช้ต่อ แต่สำหรับ phishing แบบเจาะจงจะเป็นการโจมตีโดยมุ่งเป้าหมายเฉพาะ และจะมีการเก็บข้อมูลของเหยื่อจากแหล่งต่าง ๆ จากนั้นก็จะได้จัดสรรทำอีเมล์หรือ Link ที่เป้าหมายมีโอกาสกดและยินดีจะใส่ข้อมูลให้ได้มากกว่า

นับว่า phishing คืออันตรายในยุคปัจจุบันที่ทุกคนต้องรู้ให้ทันเพื่อความปลอดภัยของตัวเอง โดยเราสามารถจะป้องกันได้ด้วยการให้ความระมัดระวังในการใช้งานอินเทอร์เน็ตให้มากขึ้น และสังเกตให้ดีว่าอีเมล์หรือ Link ที่เราได้รับมานั้นมีความน่าเชื่อถือมากน้อยเพียงใด และให้อ่านทุกข้อความโดยละเอียดอย่าใจร้อน ก็จะสามารถช่วยระวังภัยได้ในระดับหนึ่งแล้ว
