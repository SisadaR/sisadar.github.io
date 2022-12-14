---
layout: post
title: สิบขั้นตอนการออกแบบเกม - by Jamey Stegmaier (คัดย่อ)
author: sisada
image: assets/boardgames/etc/jamey-stegmaier.jpg
categories: [board games]
tags: [กบเล่าเรื่อง]
---
ช่วงนี้ความสนใจผมเอนเอียงมาในทางฝั่งพัฒนาเกมกระดานนิดหน่อย (คือปกติจะสนใจในแง่กลไกการเล่นเป็นหลัก แต่ว่าก็ยังไม่ได้กะออกแบบอะไรเองนะ ความขี้เกียจยังมีชัย) ส่วนหนึ่งน่าจะเพราะช่วงนี้ไปเจอคนที่อยากเป็นนักออกแบบหลายคนอยู่  พอหา keyword ผ่านๆก็ไปเจออันนี้มา  คิดว่าทำโน๊ตย่อเก็บไว้หน่อยก็คงดี หลายๆข้อก็อาจจะไม่เหมาะกับเมืองไทยเท่าไร แต่ก็สามารถปรับใช้เอาได้อยู่ หลายอันก็รู้สึกว่าเค้าซอยหัวข้อแปลกๆ.....แต่ก็เอาน่ะ

> ส่วนนาย Jamey Stegmaier นี้ก็เจ้าของค่าย Stonemaier Game และเป็นคนออกแบบ Scythe กับ Viticulture เกมดังที่หลายคนน่าจะเคยสัมผัสกันมาแล้ว ไม่ว่าจะชอบหรือไม่ชอบเกมของเค้าก็ตาม ก็ต้องยอมรับว่างานของเค้ามี impact กับวงการหลายอย่างจริงๆ (blog เค้าก็ดีนะ แนะนำให้ไปอ่าน)


https://www.youtube.com/watch?v=SUZjn6m\_Qvs

> อันนี้ผมสรุปย่อไปเยอะ แต่ก็คิดว่าครบถ้วนพอควร สามารถดูคลิปเก็บตกที่เหลือเองได้เลย


**1) เล่นเกมให้เยอะ:** ลองเกมให้หลากหลาย ทั้งธีม, ระบบ, จำนวนคน เพื่อที่เราจะได้มีไอเดียไว้เพื่อผสมผสานในแบบที่เราต้องการ รวมถึงไปเสนอตัวช่วยนักออกแบบคนอื่น เพื่อช่วยทดสอบเกมให้ ข้อดีคือคุณจะได้เรียนรู้การออกแบบเกมของคนอื่น รวมไปถึงวิธีการให้ข้อมูลที่จำเป็นแก่นักพัฒนา แถมยังเป็นการสร้างเครือข่ายเวลาที่เราต้องการหาคนมาเทสเกมของเราบ้าง

**2) ไปสมัครสามที่นี้ เพราะมีแหล่งข้อมูลให้ตามอ่านต่อมากมาย:**
[http://www.ludology.libsyn.com](http://www.ludology.libsyn.com/)
podcast ที่คุยเกี่ยวกับการออกแบบเกม


[http://www.todayinboardgames.com](http://www.todayinboardgames.com/)
เวบข่าวที่เต็มไปด้วยบทความ และบทสัมภาษณ์นักออกแบบ รวมไปถึงข่าว Kickstarter


[http://www.cardboardedison.tumblr.com](http://www.cardboardedison.tumblr.com/)
เต็มไปด้วยทิปดีๆสำหรับการออกแบบเกมมากมาย


**3) Brainstorm Idea:** เทคนิคของเจมมี่คือใช้ดินสอกับกระดาษธรรมดาเนี่ยล่ะ แล้วก็วาดแนวคิดลงบนกระดานไวท์บอร์ดเพื่อให้เห็นภาพรวม แนวคิดของเค้า(ที่ไม่จำเป็นต้องทำเหมือนกันทุกคน) คือเน้นการเชื่อมต่อของกลไกกับธีม โดยพยายามเลือกธีมที่ขายได้แล้วพัฒนากลไกมารองรับ (สังเกตุว่าเค้าไม่ได้หมายถึงต้องเอาหลายๆคนมารวมหัวกันนะ)

**4) Rapid Prototyping:** รีบนำไอเดียที่คิดออกมาทดสอบให้เร็วที่สุด วิธีนี้จะช่วยให้คุณรู้ว่าเกมที่มันเล่นจริงแตกต่างกับที่คุณนึกภาพไว้ในหัวอย่างไร และจงเขียนกติกาออกมาด้วย เพราะมันจะทำให้คุณมองเห็นจุดผิดพลาด หรือส่วนที่ซับซ้อนเกินจำเป็นในเวลาที่คุณพยายามจะอธิบายมันออกมาเป็นคำพูดจริง

**5)** ได้เวลาเอาตัวทดสอบไปให้คนในกลุ่มเล่น

**6)** เมื่อคุณรู้สึกว่าเกมสนุกในระดับหนึ่งแล้วก็ได้เวลาออกไปหา blind playtester ซึ่งก็คือการทดสอบกับคนที่คุณไม่รู้จัก จุดสำคัญคือคนกลุ่มนี้จะต้องเรียนรู้วิธีเกมเองจากการอ่านคู่มือที่คุณเขียน ด้วยวิธีนี้คนกลุ่มนี้จะถามคำถามกลับมาหาคุณ (ซึ่งเยอะแน่ๆ) เพราะว่าพวกเค้าจะเล่นเกมในแบบที่แตกต่างไปจากกลุ่มที่คุณเล่นด้วยประจำ ในข้อ 5 ซึ่งคำถามและคำแนะนำพวกนี้ก็จะมีประโยชน์กับเราแน่นอนในปรับปรุงงานที่ทำอยู่ (ตรงนี้ถ้าเคยทำข้อ 1 มาก่อนคุณก็จะหาคนช่วยเทสได้ง่ายขึ้น)

**7) เตรียมขาย:** ตรงนี้จะต้องเลือกระหว่างทำขายเองหรือว่าจะหาสำนักพิมพ์ ถ้าจะขายเองก็ได้เวลาเตรียมหางานศิลป์มาใส่ ในขณะที่ถ้าจะขายงานให้สำนักพิมพ์ทางนั้นจะเป็นคนจัดการส่วนที่เหลือเอง

**8) ติดต่อโรงงาน:** ในกรณีนี้เจมมี่เค้าใช้บริษัท Panda ของจีน (มีอีกหลายเจ้าแต่เจ้านี้ก็ถือว่าเป็นตัวเลือกยอดนิยมเจ้าหนึ่ง) หลังจากได้ราคามาแล้วเราจะเริ่มเห็นว่าอะไรถูก อะไรแพง หรือตรงไหนที่เราควรจะตัดเพื่อให้เกมอยู่ในงบประมาณของเรา หรือส่วนไหนจะพักไว้ก่อนรอออกเป็นตัวเสริมดี

**9) ออก Kickstarter:** ไม่จำเป็นต้องอาร์ทให้เสร็จหมด เพราะมันจะแพงมาก แต่ควรจะใช้อาร์ทสวยๆที่แสดงถึงเกมแล้วก็ธีมของเกมแค่ไม่กี่ชิ้นก็พอแล้ว ส่วนการหานักวาดเค้าแนะนำให้มองหาเกมที่ชอบแล้วก็ติดต่อคนวาดไปเลย หรือไม่ก็ไปตามหารูปในเวบที่รวมงานจากศิลปินแล้วติดต่อคนที่คิดว่าแนวทางเหมาะกับสิ่งที่เราจะสื่อ

**10) แหล่งข้อมูลสำหรับการจัดการ Kickstarter:**
* เจมมี่แนะนำให้ไปดูที่เวบของเค้า kickstarterlessons.com (อันนี้ผมก็ว่ามีข้อมูลดีๆเยอะดี)
* Podcast ชื่อ Funding the Dream on Kickstarter ([www.buzzsprout.com/4646](http://www.buzzsprout.com/4646))




---



> อีกเรื่องหนึ่งที่เกี่ยวกับการผลิตผลงานเอง (ข้อ 7,8,9,10 ข้างบน) ลิงค์นี้ก็น่าสนใจดี ว่าด้วยการเป็น publisher เองด้วยเงิน $1000 (ชื่อชวนให้รู้สึกถึงรายการญี่ปุ่นอยู่ด้วยเงิน 1000 เยนอย่างไรชอบกล) ในแง่ค่าเงินไม่ค่อยสำคัญเท่าไร แต่เค้าอธิบายวงจรของการทำงานได้ครบถ้วนดี http://hyperbolegames.com/blog/1000-test




---


**อันนี้พล่ามเรื่อยเปื่อย ไม่เกี่ยวกับข้างบนเท่าไร:**

ในลิงค์ youtube มีคนมา comment เกี่ยวกับว่าเราจะปกป้องไอเดียเกมของเราได้อย่างไร ซึ่งเจมมี่เค้าก็ตอบได้ตรงกับความคิดผมดีนั้นคือ

> **ไม่มีใครแคร์ไอเดียคุณหรอก เค้าสนแต่การกระทำ** และถ้าคุณต้องการจะปกป้องมันมากล่ะก็จงแชร์มันออกไปให้มากที่สุด เพราะเวลามีคนเอางานของคุณไปใช้ชุมชนบอร์ดเกมก็จะเป็นกระบอกเสียงให้คุณเอง


อันนี้พูดในฐานะ 'คนวงนอก' นะ คือผมติดตามข่าวบ้าง แต่ก็ไม่ได้เข้าไปคลุกคลีมีตติ้งกับกลุ่มออกแบบเกมของไทยเท่าไร เหตุผลคือผมยังไม่ได้อยากออกแบบอะไร กับรู้สึกว่ายังไม่ใครทำเกมแบบที่ผมสนใจชวนให้ไปติดตาม

ความเลื่อมล้ำอย่างหนึ่งใน community นักออกแบบบ้านเราที่ผมรู้สึกคือ ทักษะทางภาษา -- กลุ่มที่อ่านออกก็เข้าถึงข้อมูลดีๆในการออกแบบไปเรียบร้อย แต่ว่าเอาแค่เวลาจะเสพ มีเท่าไรก็ไม่พอ แถมการแปลเรื่องยากๆก็ไม่เห็นจะสนุกตรงไหน (ยังไม่นับว่าแปลเท่าไรก็ไม่พอเพราะมีดีๆเยอะมาก)  กลุ่มที่อ่านภาษาไม่ออกก็เลยได้แต่วนเวียนอยู่กับแนวคิดเดิมๆ พร้อมกับคำถามเดิมๆ

กลายเป็นว่าพื้นที่ และหัวข้อในการคุยแบบมีสาระเป็นภาษาไทยไม่ค่อยมี เพราะคุยกันไม่ค่อยรู้เรื่อง คนที่ได้ภาษาก็หนีไปคุยกับฝรั่งเลยสบายกว่า

อย่างตอนผมดูคลิปข้างบนเนี่ย ตอนฟังไปครึ่งแรกแถวๆข้อหกเนี่ยรู้สึกว่าเออดีหว่ะ น่าแปล แต่พอนั่งแปลไปซักพักแล้วก็มาคิดได้ว่า แล้วกูจะแปลให้ใครอ่าน? คืออันนี้มันหัวข้อแบบแอบจริงจังนิดนึงไง คนได้ภาษาเปิดดูคลิปแป๊บเดียวก็ได้ (โอเคผมทำสรุปไว้ก็ถือว่าช่วย overview ให้ เลยประหยัดเวลานิดนึง) แต่คนฟังไม่ออกการที่เค้ารู้มันช่วยอะไรได้?

ใครมีมุมมองอะไรก็บอกกันได้ครับยินดีพูดคุย

 