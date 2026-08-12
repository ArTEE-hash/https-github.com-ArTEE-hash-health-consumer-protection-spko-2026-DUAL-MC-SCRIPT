<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>บทพิธีกรคู่ โครงการพัฒนาสมรรถนะเครือข่ายคุ้มครองผู้บริโภคฯ 13-14 สิงหาคม 2569</title>
<link href="https://fonts.googleapis.com/css2?family=Sarabun:wght@300;400;600;700;800&family=Noto+Serif+Thai:wght@400;600;700&display=swap" rel="stylesheet">
<style>
  :root {
    --gold: #C9922A; --gold-light: #F0C96A; --gold-pale: #FDF3DC;
    --teal: #1A6B6B; --teal-light: #2A9090; --cream: #FEFAF3;
    --ink: #1A1208; --muted: #7A6848; --mc1: #8B1A4A; --mc2: #1A4A6B; --border: #D4B87A;
  }
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body { font-family: 'Sarabun', sans-serif; background: var(--cream); color: var(--ink); line-height: 1.8; }

  @media print {
    .no-print { display: none !important; }
    body { background: white; }
    .cover { page-break-after: always; }
    .segment { page-break-inside: avoid; }
    .page-break { page-break-before: always; }
  }

  /* EDIT TOOLBAR */
  .edit-toolbar {
    position: fixed; top: 0; left: 0; right: 0; z-index: 1000;
    background: #1A3A3A; color: white; padding: 10px 20px;
    display: flex; align-items: center; gap: 12px; font-size: 13px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.2);
  }
  .edit-toolbar .hint { flex: 1; opacity: 0.85; }
  .edit-toolbar button {
    font-family: 'Sarabun', sans-serif; font-size: 13px; font-weight: 700;
    border: none; border-radius: 20px; padding: 8px 16px; cursor: pointer;
  }
  #editBtn { background: var(--gold); color: #1A1208; }
  #editBtn.on { background: #E85D5D; color: white; }
  #exportBtn { background: var(--teal-light); color: white; }
  body.toolbar-active { padding-top: 46px; }
  body.toolbar-active .print-btn { bottom: 84px; }

  [contenteditable="true"] { outline: none; }
  body.edit-mode [contenteditable="true"]:hover { outline: 2px dashed var(--gold); cursor: text; border-radius: 4px; }
  body.edit-mode [contenteditable="true"]:focus { outline: 2px solid var(--teal); background: #fffef0; border-radius: 4px; }

  .cover {
    background: linear-gradient(160deg, #0A3D3D 0%, #1A6B6B 40%, #0D2A2A 100%);
    color: white; min-height: 100vh; display: flex; flex-direction: column;
    align-items: center; justify-content: center; text-align: center;
    padding: 60px 40px; position: relative; overflow: hidden;
  }
  .cover::before {
    content: ''; position: absolute; inset: 0;
    background-image: radial-gradient(circle at 20% 20%, rgba(201,146,42,0.15) 0%, transparent 50%),
      radial-gradient(circle at 80% 80%, rgba(201,146,42,0.10) 0%, transparent 50%);
  }
  .cover-ornament { font-size: 52px; margin-bottom: 18px; filter: drop-shadow(0 4px 12px rgba(240,201,106,0.6)); }
  .cover-label { font-size: 13px; letter-spacing: 4px; text-transform: uppercase; color: var(--gold-light); margin-bottom: 14px; font-weight: 600; }
  .cover-title-th { font-family: 'Noto Serif Thai', serif; font-size: 30px; font-weight: 700; color: var(--gold-light); line-height: 1.4; margin-bottom: 8px; text-shadow: 0 2px 20px rgba(240,201,106,0.4); }
  .cover-subtitle { font-size: 17px; color: rgba(255,255,255,0.85); margin-bottom: 24px; font-weight: 300; }
  .cover-divider { width: 110px; height: 3px; background: linear-gradient(90deg, transparent, var(--gold-light), transparent); margin: 20px auto; }

  .cover-info { background: rgba(255,255,255,0.08); border: 1px solid rgba(240,201,106,0.3); border-radius: 16px; padding: 24px 36px; backdrop-filter: blur(8px); margin-bottom: 24px; max-width: 560px; }
  .cover-info p { color: rgba(255,255,255,0.9); font-size: 15px; margin: 5px 0; }
  .cover-info strong { color: var(--gold-light); }

  .mc-roster { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; max-width: 560px; margin: 0 auto 18px; }
  .mc-card { border-radius: 12px; padding: 16px 20px; text-align: left; border: 1px solid; }
  .mc-card.mc1 { background: rgba(139,26,74,0.25); border-color: rgba(139,26,74,0.5); }
  .mc-card.mc2 { background: rgba(26,74,107,0.25); border-color: rgba(26,74,107,0.5); }
  .mc-card-role { font-size: 11px; font-weight: 700; letter-spacing: 2px; text-transform: uppercase; color: var(--gold-light); margin-bottom: 4px; }
  .mc-card-name { font-size: 15px; font-weight: 700; color: white; margin-bottom: 2px; }
  .mc-card-nick { font-size: 12px; color: rgba(255,255,255,0.6); }

  .format-note { max-width: 560px; display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; }
  .format-pill { font-size: 12px; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(240,201,106,0.4); color: rgba(255,255,255,0.85); }

  .content { max-width: 900px; margin: 0 auto; padding: 48px 40px 80px; }

  .toc { background: white; border: 2px solid var(--border); border-radius: 16px; padding: 32px; margin-bottom: 48px; box-shadow: 0 4px 24px rgba(201,146,42,0.08); }
  .toc-title { font-family: 'Noto Serif Thai', serif; font-size: 20px; font-weight: 700; color: var(--teal); margin-bottom: 20px; display: flex; align-items: center; gap: 10px; }
  .toc-item { display: flex; align-items: center; padding: 10px 0; border-bottom: 1px dashed var(--border); gap: 14px; }
  .toc-item:last-child { border-bottom: none; }
  .toc-num { width: 32px; height: 32px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 13px; font-weight: 700; color: white; flex-shrink: 0; }
  .toc-time { font-size: 13px; color: var(--muted); margin-left: auto; white-space: nowrap; }

  .segment { margin-bottom: 56px; }
  .segment-header { display: flex; align-items: flex-start; gap: 18px; margin-bottom: 22px; padding-bottom: 20px; border-bottom: 2px solid var(--border); }
  .segment-num { width: 56px; height: 56px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 22px; font-weight: 800; color: white; flex-shrink: 0; font-family: 'Noto Serif Thai', serif; box-shadow: 0 4px 12px rgba(0,0,0,0.2); }
  .segment-info { flex: 1; }
  .segment-label { font-size: 11px; font-weight: 700; letter-spacing: 3px; text-transform: uppercase; color: var(--muted); margin-bottom: 4px; }
  .segment-title { font-family: 'Noto Serif Thai', serif; font-size: 22px; font-weight: 700; line-height: 1.3; }
  .segment-time { display: inline-flex; align-items: center; gap: 6px; background: var(--gold-pale); border: 1px solid var(--border); border-radius: 20px; padding: 4px 14px; font-size: 13px; font-weight: 600; color: var(--gold); margin-top: 8px; }

  .line { margin: 12px 0; display: flex; gap: 0; align-items: flex-start; }
  .speaker-tag { display: inline-flex; align-items: center; gap: 6px; padding: 4px 14px; border-radius: 20px 0 0 20px; font-size: 12px; font-weight: 700; white-space: nowrap; min-width: 110px; flex-shrink: 0; color: white; margin-top: 2px; }
  .speaker-tag.all { background: linear-gradient(90deg, #555, #333); min-width: 110px; }
  .speech-bubble { background: white; border: 1px solid; border-left: none; border-radius: 0 12px 12px 0; padding: 10px 18px; font-size: 15px; line-height: 1.85; flex: 1; color: var(--ink); }

  .mc1-tag { background: var(--mc1); }
  .mc1-bubble { border-color: rgba(139,26,74,0.25); background: rgba(139,26,74,0.03); }
  .mc2-tag { background: var(--mc2); }
  .mc2-bubble { border-color: rgba(26,74,107,0.25); background: rgba(26,74,107,0.03); }

  .direction { background: #f5f0e8; border-left: 4px solid var(--gold); border-radius: 0 8px 8px 0; padding: 10px 18px; font-style: italic; font-size: 13px; color: var(--muted); margin: 12px 0; }

  .cue-box { background: #eef2ef; border: 1px dashed #9AAE9E; border-radius: 10px; padding: 12px 18px; margin: 10px 0 10px 114px; font-size: 12.5px; color: #3E5348; }
  .cue-box strong { color: #2A5A4A; }

  .backup-box { background: #FDF6E3; border: 1px solid #E3C878; border-radius: 10px; padding: 12px 18px; margin: 10px 0 10px 114px; font-size: 13px; color: #6B4E10; }
  .backup-box strong { color: #A2760F; }

  .note-box { background: linear-gradient(135deg, #e8f4f4, #d4eaea); border: 1px solid var(--teal-light); border-radius: 12px; padding: 16px 20px; margin: 16px 0; font-size: 13px; color: var(--teal); }
  .note-box strong { color: var(--teal); }

  .name-list { background: var(--gold-pale); border: 1px solid var(--border); border-radius: 12px; padding: 16px 20px; margin: 12px 0 12px 114px; font-size: 14px; line-height: 2.1; }
  .name-list ol { padding-left: 20px; }
  .name-list .sub { color: var(--muted); font-size: 12.5px; }

  .section-divider { display: flex; align-items: center; gap: 16px; margin: 32px 0 20px; }
  .section-divider::before, .section-divider::after { content: ''; flex: 1; height: 1px; background: var(--border); }
  .section-divider span { font-size: 12px; font-weight: 700; letter-spacing: 3px; text-transform: uppercase; color: var(--muted); white-space: nowrap; }

  .print-btn { position: fixed; bottom: 32px; right: 32px; background: var(--teal); color: white; border: none; border-radius: 50px; padding: 14px 28px; font-family: 'Sarabun', sans-serif; font-size: 15px; font-weight: 700; cursor: pointer; box-shadow: 0 4px 20px rgba(26,107,107,0.4); display: flex; align-items: center; gap: 8px; z-index: 999; }
  .print-btn:hover { background: var(--teal-light); transform: translateY(-2px); }

  .seg0 .segment-num { background: linear-gradient(135deg, #4A7C6B, #2A5A4A); }
  .seg0 .segment-title { color: #2A5A4A; }
  .seg1 .segment-num { background: linear-gradient(135deg, #2A1A6B, #1A0F4A); }
  .seg1 .segment-title { color: #2A1A6B; }
  .seg2 .segment-num { background: linear-gradient(135deg, #8B4A1A, #6B2A0A); }
  .seg2 .segment-title { color: #6B2A0A; }
  .seg3 .segment-num { background: linear-gradient(135deg, #8B1A4A, #6B0A2A); }
  .seg3 .segment-title { color: #6B0A2A; }
  .seg4 .segment-num { background: linear-gradient(135deg, #1A6B3A, #0A4A2A); }
  .seg4 .segment-title { color: #0A4A2A; }

  .appendix { background: white; border: 2px solid var(--border); border-radius: 16px; padding: 32px; margin-top: 24px; }
  .appendix h3 { font-family: 'Noto Serif Thai', serif; color: var(--teal); font-size: 18px; margin: 20px 0 10px; }
  .appendix h3:first-child { margin-top: 0; }
  .appendix table { width: 100%; border-collapse: collapse; font-size: 13.5px; margin-bottom: 8px; }
  .appendix th, .appendix td { border: 1px solid var(--border); padding: 8px 10px; text-align: left; }
  .appendix th { background: var(--gold-pale); color: var(--muted); font-weight: 700; }
  .appendix ul { padding-left: 22px; font-size: 13.5px; line-height: 1.9; }
  .appendix .small-note { font-size: 12.5px; color: var(--muted); font-style: italic; margin: 6px 0 18px; }
</style>
</head>
<body>

<div class="edit-toolbar no-print" id="toolbar">
  <span class="hint">✏️ กดปุ่ม "แก้ไขข้อความ" เพื่อพิมพ์แก้ไขบทพูด ชื่อ หรือเวลาได้โดยตรงในหน้านี้ แล้วกด "ดาวน์โหลดฉบับแก้ไข" เพื่อบันทึกเป็นไฟล์ใหม่</span>
  <button id="editBtn" onclick="toggleEdit()">✏️ แก้ไขข้อความ</button>
  <button id="exportBtn" onclick="exportHtml()">⬇️ ดาวน์โหลดฉบับแก้ไข</button>
</div>

<div class="cover">
  <div class="cover-ornament">🌿</div>
  <div class="cover-label">บทพิธีกรคู่ (Dual MC Script) · ฉบับใช้งานจริง</div>
  <div class="cover-title-th editable">โครงการพัฒนาสมรรถนะเครือข่ายคุ้มครองผู้บริโภค<br>ด้านผลิตภัณฑ์สุขภาพ</div>
  <div class="cover-subtitle editable">เขตสุขภาพกลุ่มจังหวัดภาคกลาง ปีงบประมาณ 2569 | สำนักงานสาธารณสุขจังหวัดสมุทรปราการ</div>
  <div class="cover-divider"></div>
  <div class="cover-info">
    <p class="editable">📅 <strong>วันที่ 13 – 14 สิงหาคม 2569</strong></p>
    <p class="editable">📍 <strong>ห้องราชาเทวะ โรงแรมมิราเคิล สุวรรณภูมิ</strong></p>
  </div>

  <div class="mc-roster">
    <div class="mc-card mc1">
      <div class="mc-card-role">MC 1 · พิธีกรหลัก</div>
      <div class="mc-card-name editable">นางจิตราวรรณ ฉันทจิตรปรีชา</div>
      <div class="mc-card-nick editable">พี่ใหม่ · นักวิชาการสาธารณสุขชำนาญการ</div>
    </div>
    <div class="mc-card mc2">
      <div class="mc-card-role">MC 2 · พิธีกรหลัก</div>
      <div class="mc-card-name editable">นายศรัณยู โสตะวงศ์</div>
      <div class="mc-card-nick editable">พี่ยู · แพทย์แผนไทยชำนาญการ</div>
    </div>
  </div>

  <div class="format-note">
    <div class="format-pill">🎓 ภาคประชุมวิชาการ: เป็นทางการ อบอุ่น สุภาพ</div>
    <div class="format-pill">🎉 ภาคเลี้ยงค่ำ: เป็นกันเอง สนุกสนาน คึกคัก</div>
  </div>
</div>

<div class="content">

  <div class="toc">
    <div class="toc-title">📋 สารบัญ</div>
    <div class="toc-item"><div class="toc-num" style="background:#2A5A4A;">0</div><div class="editable">วันที่ 1 · ลงทะเบียน และพิธีเปิดการประชุม</div><div class="toc-time">08.00 – 09.15 น.</div></div>
    <div class="toc-item"><div class="toc-num" style="background:#2A1A6B;">1</div><div class="editable">วันที่ 1 · อภิปราย 1: กฎหมายเครื่องสำอางในสถานพยาบาลเสริมความงาม</div><div class="toc-time">09.15 – 12.00 น.</div></div>
    <div class="toc-item"><div class="toc-num" style="background:#6B2A0A;">2</div><div class="editable">วันที่ 1 · อภิปราย 2: สถานการณ์พืชกระท่อมหลังปลดล็อก</div><div class="toc-time">13.00 – 18.00 น.</div></div>
    <div class="toc-item"><div class="toc-num" style="background:#6B0A2A;">3</div><div class="editable">วันที่ 1 · ภาคเลี้ยงค่ำ / มุทิตาจิตผู้เกษียณ</div><div class="toc-time">18.00 – 22.00 น.</div></div>
    <div class="toc-item"><div class="toc-num" style="background:#0A4A2A;">4</div><div class="editable">วันที่ 2 · บรรยาย ประชุมกลุ่มย่อย และปิดการประชุม</div><div class="toc-time">09.00 – 12.00 น.</div></div>
  </div>

  <!-- ============================================ -->
  <!-- SEGMENT 0 -->
  <!-- ============================================ -->
  <div class="segment seg0" id="seg0">
    <div class="segment-header">
      <div class="segment-num">0</div>
      <div class="segment-info">
        <div class="segment-label">วันที่ 1 · 13 สิงหาคม 2569 · ภาคประชุมวิชาการ</div>
        <div class="segment-title editable">ลงทะเบียน และพิธีเปิดการประชุม</div>
        <div class="segment-time editable">⏰ 08.00 – 09.15 น.</div>
      </div>
    </div>

    <div class="note-box">🎙️ <strong>โทนการพูด:</strong> เป็นทางการ อบอุ่น สุภาพ ใช้ราชาศัพท์และคำแทนตัวที่เหมาะสมตลอดภาคกลางวัน</div>

    <div class="section-divider"><span>ต้อนรับผู้เข้าร่วมประชุม</span></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">สวัสดีครับ ขอต้อนรับทุกท่านเข้าสู่การประชุมเชิงปฏิบัติการ <strong>โครงการพัฒนาสมรรถนะเครือข่ายคุ้มครองผู้บริโภค ด้านผลิตภัณฑ์สุขภาพ เขตสุขภาพกลุ่มจังหวัดภาคกลาง ประจำปีงบประมาณ 2569</strong> ระหว่างวันที่ 13 – 14 สิงหาคม 2569 ณ ห้องราชาเทวะ โรงแรมมิราเคิล สุวรรณภูมิ แห่งนี้ครับ ผม <strong>นายศรัณยู โสตะวงศ์</strong> แพทย์แผนไทยชำนาญการ จากสำนักงานสาธารณสุขจังหวัดสมุทรปราการครับ</div></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">และดิฉัน <strong>นางจิตราวรรณ ฉันทจิตรปรีชา</strong> นักวิชาการสาธารณสุขชำนาญการ จากสำนักงานสาธารณสุขจังหวัดสมุทรปราการค่ะ เราสองคนรับหน้าที่เป็นพิธีกรดูแลทุกท่านตลอดสองวันของการประชุมในครั้งนี้ ร่วมกับทีมงานทุก ๆ ท่านจากกลุ่มงานคุ้มครองผู้บริโภคฯ ค่ะ</div></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ขณะนี้อยู่ในช่วงเวลาลงทะเบียนค่ะ ขอเชิญทุกท่านลงทะเบียนและรับเอกสารประกอบการประชุมได้ที่โต๊ะด้านหน้าห้องประชุมนะคะ แล้วพบกันในพิธีเปิดเวลา 09.00 น. ค่ะ</div></div>

    <div class="cue-box editable">🔧 <strong>Cue เจ้าหน้าที่:</strong> เตรียมโต๊ะลงทะเบียน เอกสาร และป้ายชื่อ · ตรวจสอบระบบเสียง ไมโครโฟน โปรเจกเตอร์ · ประสานผู้บริหารและวิทยากรช่วงเช้า</div>

    <div class="section-divider"><span>พิธีเปิดการประชุม</span></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">ได้เวลาอันสมควรแล้วครับ ขอเรียนเชิญทุกท่านเข้าสู่พิธีเปิดการประชุมอย่างเป็นทางการครับ ขอเรียนเชิญ <strong>นายแพทย์ประภาส ผูกดวง นายแพทย์สาธารณสุขจังหวัดสมุทรปราการ</strong> ประธานในพิธี ขึ้นประจำที่โพเดียมด้านบนเวที เพื่อรับฟังรายงานวัตถุประสงค์การจัดโครงการ และกล่าวเปิดการประชุมเชิงปฏิบัติการในวันนี้ครับ ขอเรียนเชิญครับ</div></div>

    <div class="cue-box editable">🔧 <strong>Cue เจ้าหน้าที่:</strong> เชิญประธานและผู้กล่าวรายงานขึ้นเวที ประจำโพเดียมด้านข้างเวที · เชิญทุกท่านปรบมือต้อนรับ</div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">และในโอกาสนี้ ขอเรียนเชิญ <strong>นางสาวณัฐยาภรณ์ วงศ์บุญเกื้อกูล</strong> หัวหน้ากลุ่มงานคุ้มครองผู้บริโภคและเภสัชสาธารณสุข กล่าวรายงานวัตถุประสงค์การจัดโครงการในครั้งนี้ค่ะ ขอเรียนเชิญค่ะ</div></div>

    <div class="direction">⏸️ (หลังกล่าวรายงานเสร็จ)</div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ขอบคุณหัวหน้ากลุ่มงานคุ้มครองผู้บริโภคฯ สำหรับการกล่าวรายงานค่ะ ลำดับต่อไป ขอเรียนเชิญท่านประธานในพิธี <strong>นายแพทย์ประภาส ผูกดวง นายแพทย์สาธารณสุขจังหวัดสมุทรปราการ</strong> กล่าวเปิดการประชุมเชิงปฏิบัติการในวันนี้ค่ะ ขอเรียนเชิญค่ะ</div></div>

    <div class="direction">⏸️ (ประธานกล่าวเปิดงาน — MC ยืนสงบนิ่งในจุดที่เหมาะสม)</div>
  </div><!-- /seg0 -->

  <!-- ============================================ -->
  <!-- SEGMENT 1 -->
  <!-- ============================================ -->
  <div class="segment seg1 page-break" id="seg1">
    <div class="segment-header">
      <div class="segment-num">1</div>
      <div class="segment-info">
        <div class="segment-label">วันที่ 1 · ภาคประชุมวิชาการ</div>
        <div class="segment-title editable">อภิปราย 1: กระบวนการบังคับใช้กฎหมาย<br>ผลิตภัณฑ์เครื่องสำอางในสถานพยาบาลเสริมความงาม</div>
        <div class="segment-time editable">⏰ 09.15 – 12.00 น.</div>
      </div>
    </div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">ขอกราบขอบพระคุณท่านประธานเป็นอย่างสูงครับ ถือว่าการประชุมเชิงปฏิบัติการในวันนี้ได้เปิดขึ้นอย่างเป็นทางการแล้วนับตั้งแต่บัดนี้ครับ</div></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ลำดับต่อไป ขอเรียนเชิญเข้าสู่ช่วงอภิปรายทางวิชาการหัวข้อแรกของวันนี้ค่ะ ในหัวข้อ <strong>"กระบวนการบังคับใช้กฎหมายผลิตภัณฑ์เครื่องสำอางในสถานพยาบาลเสริมความงาม"</strong> ซึ่งเป็นประเด็นที่เครือข่ายคุ้มครองผู้บริโภคให้ความสำคัญเป็นอย่างมากในปัจจุบันค่ะ</div></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">ขอแนะนำผู้ร่วมอภิปรายทั้งสองท่านครับ ท่านแรก <strong>คุณรุ่งดารา เนียมโภคะ</strong> เภสัชกรชำนาญการพิเศษ หัวหน้ากลุ่มเฝ้าระวังและบังคับใช้กฎหมาย และท่านที่สอง <strong>คุณวรางคณา เทวราชสมบูรณ์</strong> เภสัชกรชำนาญการพิเศษ จากกลุ่มเฝ้าระวังและบังคับใช้กฎหมาย กองควบคุมเครื่องสำอางและวัตถุอันตราย สำนักงานคณะกรรมการอาหารและยา กระทรวงสาธารณสุขครับ โดยได้รับเกียรติจาก <strong>คุณเยาวนาถ ลาภานันต์</strong> เภสัชกรชำนาญการพิเศษ จากสำนักงานสาธารณสุขจังหวัดระยอง เป็นผู้ดำเนินรายการในช่วงนี้ครับ</div></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ขอเรียนเชิญวิทยากรทุกท่านขึ้นสู่เวทีเสวนาค่ะ ขอเสียงปรบมือต้อนรับด้วยค่ะ</div></div>

    <div class="direction">⏸️ (วิทยากรขึ้นเวที เริ่มการอภิปราย)</div>

    <div class="backup-box editable">🕥 <strong>คิวแทรก 10.30–10.45 น. พักอาหารว่างเช้า:</strong> "ขออนุญาตแทรกสักครู่นะคะ เพื่อให้การอภิปรายมีความต่อเนื่อง ทุก ๆ ท่านสามารถนำอาหารว่างที่ทางผู้จัดได้เตรียมไว้ด้านหลังห้องประชุมเข้ามารับประทานในระหว่างการอภิปรายได้เลยนะคะ"</div>

    <div class="direction">⏸️ (หลังเสวนาเสร็จสิ้น)</div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">ขอขอบพระคุณวิทยากรทั้งสองท่าน และคุณเยาวนาถ ผู้ดำเนินรายการ เป็นอย่างสูงครับ สำหรับการอภิปรายที่เป็นประโยชน์อย่างยิ่งต่อการปฏิบัติงานคุ้มครองผู้บริโภคในพื้นที่ครับ ขอเสียงปรบมือให้กับวิทยากรทุกท่านอีกครั้งครับ 👏</div></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">และขณะนี้ก็ได้เวลาพักรับประทานอาหารกลางวันแล้วค่ะ ขอเชิญทุกท่านรับประทานอาหารกลางวันร่วมกัน และขอเชิญกลับเข้าห้องประชุมภายในเวลา 13.00 น. เพื่อร่วมรับฟังการอภิปรายหัวข้อต่อไปค่ะ</div></div>

    <div class="section-divider"><span>12.00 – 13.00 น. · รับประทานอาหารกลางวัน</span></div>
  </div><!-- /seg1 -->

  <!-- ============================================ -->
  <!-- SEGMENT 2 -->
  <!-- ============================================ -->
  <div class="segment seg2 page-break" id="seg2">
    <div class="segment-header">
      <div class="segment-num">2</div>
      <div class="segment-info">
        <div class="segment-label">วันที่ 1 · ภาคประชุมวิชาการ</div>
        <div class="segment-title editable">อภิปราย 2: สถานการณ์พืชกระท่อม<br>หลังปลดออกจากบัญชียาเสพติด</div>
        <div class="segment-time editable">⏰ 13.00 – 18.00 น.</div>
      </div>
    </div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">สวัสดีอีกครั้งครับ หวังว่าทุกท่านจะได้พักผ่อนรับประทานอาหารกลางวันกันอย่างเต็มอิ่มนะครับ ลำดับต่อไปเป็นการอภิปรายหัวข้อที่สองของวันนี้ ในหัวข้อ <strong>"สถานการณ์พืชกระท่อมหลังปลดออกจากบัญชียาเสพติด"</strong> ซึ่งเป็นประเด็นที่ได้รับความสนใจจากหลายภาคส่วนครับ</div></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">หัวข้อนี้ได้รับเกียรติจากผู้ทรงคุณวุฒิหลายภาคส่วนมาร่วมให้มุมมองที่หลากหลายค่ะ ใหม่ขอเรียนเชิญท่านวิทยากรทีละท่านตามลำดับ ดังนี้ค่ะ</div></div>

    <div class="name-list editable">
      <ol>
        <li><strong>นายจีระสันต์ มีรัตน์ธนวัต</strong> — หัวหน้ากลุ่มงานคุ้มครองผู้บริโภคและเภสัชสาธารณสุข สำนักงานสาธารณสุขจังหวัดชลบุรี</li>
        <li><strong>นายอภิชาติ ชัยวรรณ</strong> — นักวิเคราะห์นโยบายและแผนชำนาญการพิเศษ สำนักงาน ป.ป.ส.</li>
        <li><strong>พันตำรวจเอก วีระพงษ์ คล้ายทอง</strong> — ผู้กำกับการ 4 กองบังคับการปราบปรามการกระทำความผิดเกี่ยวกับการคุ้มครองผู้บริโภค (บก.ปคบ.)</li>
        <li><strong>นางสาวจริยา อัครวรัณธร</strong> — เภสัชกรชำนาญการพิเศษ กลุ่มคุ้มครองผู้บริโภคด้านสาธารณสุข ศูนย์วิทยาศาสตร์การแพทย์ที่ 6 ชลบุรี</li>
        <li><strong>นายชาติชาย ตั้งทรงสุวรรณ์</strong> — นักวิชาการอาหารและยาชำนาญการพิเศษ สำนักอาหาร สำนักงานคณะกรรมการอาหารและยา</li>
        <li><strong>นายวีระศักดิ์ เหล่าตระกูล</strong> — เภสัชกรเชี่ยวชาญ (ด้านเภสัชสาธารณสุข) สำนักงานสาธารณสุขจังหวัดนครปฐม</li>
      </ol>
    </div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">โดยได้รับเกียรติจาก <strong>คุณณัฐยาภรณ์ วงศ์บุญเกื้อกูล</strong> เภสัชกรชำนาญการพิเศษ ผู้ช่วยนายแพทย์สาธารณสุขจังหวัดสมุทรปราการ เป็นผู้ดำเนินรายการตลอดช่วงการอภิปรายในวันนี้ครับ ขอเรียนเชิญวิทยากรทุกท่านขึ้นเวทีครับ ขอเสียงปรบมือต้อนรับด้วยครับ</div></div>

    <div class="direction">⏸️ (วิทยากรขึ้นเวที เริ่มการอภิปราย)</div>

    <div class="backup-box editable">🕝 <strong>คิวแทรก 14.30–14.45 น. พักอาหารว่างบ่าย:</strong> "ขออนุญาตแทรกสักครู่ค่ะ ถึงเวลาพักรับประทานอาหารว่างช่วงบ่ายแล้ว เพื่อให้การอภิปรายที่เข้มข้นนี้มีความต่อเนื่อง ขอเชิญทุกท่านนำอาหารว่างมารับประทานเพื่อรับฟังการอภิปรายต่อได้เลยนะคะ"</div>

    <div class="direction">⏸️ (การอภิปรายดำเนินต่อจนถึงเวลา 18.00 น.)</div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ขอขอบพระคุณวิทยากรทุกท่าน และคุณณัฐยาภรณ์ ผู้ดำเนินรายการ เป็นอย่างสูงค่ะ สำหรับข้อมูลและมุมมองที่รอบด้านในประเด็นพืชกระท่อม ซึ่งจะเป็นประโยชน์อย่างมากต่อการทำงานคุ้มครองผู้บริโภคในพื้นที่ต่อไปค่ะ ขอเสียงปรบมืออีกครั้งค่ะ 👏</div></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">เป็นอันเสร็จสิ้นภารกิจด้านวิชาการของวันนี้แล้วนะครับ ระหว่างเวลา 18.00–19.00 น. ขอเรียนเชิญทุกท่านรับประทานอาหารเย็น และเตรียมความพร้อมสำหรับกิจกรรมภาคค่ำ ซึ่งจะเป็นงานเลี้ยงแสดงมุทิตาจิตแด่ผู้เกษียณอายุราชการ ณ ห้องราชาเทวะแห่งนี้ครับ</div></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">แล้วพบกันในบรรยากาศที่เป็นกันเองมากขึ้นในช่วงค่ำนี้นะคะ รับรองว่าบรรยากาศจะเปลี่ยนไปอย่างสิ้นเชิง สนุกสนาน อบอุ่น เป็นกันเองแน่นอนค่ะ! [ระบุธีม/การแต่งกายภาคค่ำ หากมี] ขอบคุณค่ะ</div></div>

    <div class="section-divider"><span>18.00 – 19.00 น. · รับประทานอาหารเย็น</span></div>
  </div><!-- /seg2 -->

  <!-- ============================================ -->
  <!-- SEGMENT 3 : EVENING GALA -->
  <!-- ============================================ -->
  <div class="segment seg3 page-break" id="seg3">
    <div class="segment-header">
      <div class="segment-num">3</div>
      <div class="segment-info">
        <div class="segment-label">วันที่ 1 · ภาคเลี้ยงค่ำ / มุทิตาจิตผู้เกษียณ</div>
        <div class="segment-title editable">งานเลี้ยงแสดงมุทิตาจิต<br>แด่ผู้เกษียณอายุราชการ 6 ท่าน</div>
        <div class="segment-time editable">⏰ 18.00 – 22.00 น. ณ ห้องราชาเทวะ</div>
      </div>
    </div>

    <div class="note-box">🎉 <strong>โทนการพูด:</strong> เปลี่ยนจากทางการเป็นสนุกสนาน อบอุ่น เป็นกันเอง เหมือนงานเลี้ยงครอบครัว — เล่นมุก ทักทายผู้เกษียณแบบกันเอง แต่ยังคงความสุภาพและให้เกียรติผู้อาวุโสค่ะ</div>

    <div class="section-divider"><span>18.00 น. · ต้อนรับแขก เตรียมความพร้อม</span></div>

    <div class="line"><div class="speaker-tag all">ศรัณยู & ใหม่</div><div class="speech-bubble editable" style="border-color:rgba(100,100,100,0.3);"><strong>สวัสดีค่ะ / ครับทุกท่าน! ยินดีต้อนรับสู่ค่ำคืนแห่งความประทับใจ!</strong></div></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">สวัสดีอีกครั้งครับทุกท่าน ยินดีต้อนรับเข้าสู่บรรยากาศงานเลี้ยงยามค่ำคืนนะครับ บรรยากาศตอนนี้แตกต่างจากช่วงเช้ากับบ่ายที่ผ่านมาโดยสิ้นเชิงเลยนะครับ!</div></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">คืนนี้เราจะมาร่วมกันแสดงมุทิตาจิต ส่งความรัก ความผูกพัน และคำขอบคุณให้กับพี่ ๆ ผู้เกษียณอายุราชการของเรา ที่ได้ทุ่มเททำงานเพื่อพี่น้องประชาชนมาตลอดหลายสิบปีค่ะ ระหว่างที่รอความพร้อม ขอเชิญทุกท่านรับประทานอาหารและพูดคุยกันตามอัธยาศัยก่อนนะคะ</div></div>

    <div class="cue-box editable">🔧 <strong>Cue เจ้าหน้าที่:</strong> ทีมดูแลผู้เกษียณติดเข็มกลัดหน้าอกด้านซ้าย · น้องป๊อบติดดอกไม้ให้ VIP · เชิญผู้เกษียณและเภสัชกรเชี่ยวชาญนั่งโต๊ะ VIP · พี่หงษ์แจ้งคิวพิธีกรเมื่อผู้เกษียณมาครบ · น้องโย/น้องโจ้เตรียมเพลงเปิดตัว</div>

    <div class="section-divider"><span>18.30 น. · ขบวนเปิดตัวผู้เกษียณอายุราชการ</span></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">และแล้วก็ถึงช่วงเวลาที่ทุกคนรอคอยครับ! ขอเชิญทุกท่านร่วมส่งเสียงต้อนรับผู้เกษียณอายุราชการของเราทั้ง 6 ท่าน ที่กำลังจะเดินเข้าสู่เวทีแห่งความประทับใจในค่ำคืนนี้!</div></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ขอเสียงปรบมือดัง ๆ ต้อนรับกันหน่อยค่ะ!</div></div>

    <div class="direction">🎵 (เปิดเพลงเปิดตัว — ผู้เกษียณเดินเข้างานตามนักแสดง ไปยังโต๊ะ VIP — พิธีกรแนะนำผู้เกษียณทีละท่านระหว่างเดินเข้ามา)</div>

    <div class="name-list editable">
      <ol>
        <li><strong>ภก. ดร. สุชาติ จองประเสริฐ</strong> — จากสำนักงานคณะกรรมการอาหารและยา</li>
        <li><strong>ภญ. ดวงกมล นุตราวงศ์</strong> — เภสัชกรเชี่ยวชาญ สำนักงานสาธารณสุขจังหวัดสระบุรี</li>
        <li><strong>ภญ. เรณู เดชมา</strong> — เภสัชกรเชี่ยวชาญ สำนักงานสาธารณสุขจังหวัดสิงห์บุรี</li>
        <li><strong>ภญ. วรลักษณ์ อนันตกูล</strong> — เภสัชกรเชี่ยวชาญ สำนักงานสาธารณสุขจังหวัดราชบุรี</li>
        <li><strong>ภก. ภาณุ ศรีวรรัตน์</strong> — เภสัชกรเชี่ยวชาญ สำนักงานสาธารณสุขจังหวัดจันทบุรี</li>
        <li><strong>ภญ. ปิยะวรรณ จันทรสวัสดิ์</strong> — เภสัชกรชำนาญการพิเศษ โรงพยาบาลธัญบุรี จังหวัดปทุมธานี</li>
      </ol>
      <div class="sub">หมายเหตุ: ภก. ประสาท ลิ่มดุลย์ ข้าราชการบำนาญ นั่งเป็น VIP ตั้งแต่ต้นงาน ไม่อยู่ในขบวนเปิดตัวนี้</div>
    </div>

    <div class="line"><div class="speaker-tag all">ศรัณยู & ใหม่</div><div class="speech-bubble editable" style="border-color:rgba(100,100,100,0.3);">ขอเชิญทุกท่านปรบมือต้อนรับผู้เกษียณอายุราชการของเราอีกครั้งค่ะ/ครับ!</div></div>

    <div class="direction">⏸️ (ผู้เกษียณนั่งประจำโต๊ะ VIP เรียบร้อย)</div>

    <div class="section-divider"><span>19.00 น. · กล่าวต้อนรับผู้เข้าร่วมงาน</span></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ก่อนอื่น ในนามคณะผู้จัดงาน ดิฉันและคุณศรัณยูขอกล่าวต้อนรับทุกท่านเข้าสู่ค่ำคืนแห่งความประทับใจในวันนี้อีกครั้งค่ะ คืนนี้ขอให้ทุกท่านผ่อนคลาย สนุกสนาน อิ่มอร่อย และเก็บภาพความประทับใจกลับบ้านกันเยอะ ๆ นะคะ</div></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">คืนนี้เราเตรียมทั้งการแสดงและวีดิทัศน์ความประทับใจ รวมทั้งช่วงเวลาพิเศษที่จะให้ทุกท่านได้ร่วมส่งมอบความสุขให้กับพี่ ๆ ผู้เกษียณครับ ขอให้ทุกท่านรับประทานอาหารและเครื่องดื่มไปพร้อมกับความสนุกตลอดค่ำคืนนี้กันนะครับ</div></div>

    <div class="cue-box editable">🔧 <strong>Cue เจ้าหน้าที่:</strong> น้องบุ๋มแจ้ง Serve Wine ที่โต๊ะ VIP และเสิร์ฟเครื่องดื่มแอลกอฮอล์</div>

    <div class="section-divider"><span>19.15 น. · การแสดง "จินตลีลา สีสันภาคกลาง"</span></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ลำดับต่อไป ขอเชิญทุกท่านรับชมการแสดงชุดพิเศษที่ทีมงานเตรียมมาให้ทุกท่านได้อิ่มเอมใจ กับการแสดงชุด <strong>"จินตลีลา สีสันภาคกลาง"</strong> โดยทีม S.P.A.D. น้อง ๆ นักเรียนจากโรงเรียนสมุทรปราการค่ะ ขอเชิญชมพร้อมกันเลยค่ะ!</div></div>

    <div class="direction">🎵 (การแสดง "จินตลีลา สีสันภาคกลาง")</div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">สวยงามมากเลยใช่ไหมครับทุกท่าน! ขอเสียงปรบมือดัง ๆ ให้กับน้อง ๆ นักแสดงอีกครั้งครับ 👏 ขอขอบคุณคุณครูชลดา สุขทอง ผู้ฝึกซ้อม พร้อมทีมงานโรงเรียนสมุทรปราการทุกท่านด้วยนะครับ ที่สละเวลามาสร้างความประทับใจให้กับพวกเราในวันนี้ครับ</div></div>

    <div class="cue-box editable">🔧 <strong>Cue เจ้าหน้าที่:</strong> พี่เนะดูแลเงินมอบให้นักแสดงและนักดนตรี รวมถึงอาหารและรถรับส่งสำหรับนักแสดง</div>

    <div class="section-divider"><span>19.30 น. · พิธีมุทิตาจิต</span></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ลำดับต่อไป ขอเรียนเชิญ <strong>นายรังสรรค์ วงษ์บุญหนัก</strong> รองนายแพทย์สาธารณสุขจังหวัดสมุทรปราการ กล่าวเปิดงานแสดงมุทิตาจิตแด่ผู้เกษียณอายุราชการค่ะ ขอเรียนเชิญค่ะ</div></div>

    <div class="direction">⏸️ (รองนายแพทย์สาธารณสุขจังหวัดกล่าวเปิดงาน)</div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">ขอบพระคุณท่านรองนายแพทย์สาธารณสุขจังหวัดสมุทรปราการเป็นอย่างสูงครับ ในโอกาสนี้ ขอเรียนเชิญ <strong>ภก. ประสาท ลิ่มดุลย์</strong> ข้าราชการบำนาญ ในฐานะรุ่นพี่ผู้อาวุโส กล่าวแสดงมุทิตาจิตแด่ผู้เกษียณอายุราชการรุ่นน้องในปีนี้ครับ ขอเรียนเชิญครับ</div></div>

    <div class="direction">⏸️ (ภก.ประสาทกล่าวแสดงมุทิตาจิต)</div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ขอบพระคุณค่ะ และหลังจากนี้ ขอเชิญทุกท่านร่วมรับชมวีดิทัศน์ที่ทีมงานตั้งใจรวบรวมประวัติ ผลงาน และความประทับใจของพี่ ๆ ผู้เกษียณอายุราชการทั้ง 6 ท่านของเราค่ะ เตรียมทิชชู่ไว้ด้วยนะคะ เพราะบางช่วงอาจทำให้ใครหลายคนต้องเช็ดน้ำตา!</div></div>

    <div class="direction">🎬 (ฉายวีดิทัศน์ประวัติ ผลงาน และความประทับใจ)</div>

    <div class="cue-box editable">🔧 <strong>Cue เจ้าหน้าที่:</strong> น้องโยและน้องโจ้ดูแลความพร้อมของวีดิทัศน์</div>

    <div class="backup-box editable">🎞️ <strong>Backup หากวีดิทัศน์ขัดข้องหรือโหลดช้า:</strong> "เรียนทุกท่านครับ/ค่ะ ระหว่างที่เจ้าหน้าที่กำลังเตรียมความพร้อมของวีดิทัศน์ ขอเชิญทุกท่านยกแก้วดื่มอวยพรให้กับผู้เกษียณอายุราชการของเราไปพลาง ๆ ก่อนนะครับ/คะ"</div>

    <div class="section-divider"><span>19.45 น. · เรื่องเล่าจากใจ · ผู้เกษียณอายุราชการ</span></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">ดูวีดิทัศน์จบแล้ว เชื่อว่าหลายท่านคงอยากฟังเสียงจากพี่ ๆ ตัวจริงกันแล้วใช่ไหมครับ! และตอนนี้ก็ถึงช่วงเวลาสำคัญของค่ำคืนนี้แล้วครับ ขอเรียนเชิญผู้เกษียณอายุราชการทั้ง 6 ท่าน ขึ้นสู่เวทีเพื่อกล่าวแสดงความรู้สึกในวาระเกษียณอายุราชการครับ</div></div>

    <div class="cue-box editable">🔧 <strong>Cue เจ้าหน้าที่:</strong> น้องหงส์เดินนำและเชิญผู้เกษียณขึ้นเวที · ทีมแจกดอกไม้ (หงส์/หนิง/ป๊อบ/กวาง/บุ๋ม) แจกให้ผู้เข้าร่วมประชุมคนละ 1 ดอก · น้องยุ้ยดูแลดอกไม้แจกผู้เกษียณ</div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">หลังจากรับฟังความรู้สึกอันซาบซึ้งจากพี่ ๆ ผู้เกษียณแล้ว ลำดับต่อไป ขอเรียนเชิญนายรังสรรค์ วงษ์บุญหนัก รองนายแพทย์สาธารณสุขจังหวัดสมุทรปราการ มอบของที่ระลึกจากกลุ่มงานคุ้มครองผู้บริโภคฯ สสจ.สมุทรปราการ แด่ผู้เกษียณอายุราชการค่ะ</div></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">เรียนเชิญผู้เข้าร่วมประชุมทุกท่านร่วมถ่ายภาพกับผู้เกษียณอายุราชการเป็นที่ระลึกด้วยกันครับ</div></div>

    <div class="cue-box editable">🔧 <strong>Cue เจ้าหน้าที่:</strong> พี่ตุ๊กดูแลของที่ระลึก · พี่แอร์ดูแลถุงใส่ของที่ระลึก · พี่ตุ๊ก พี่หงษ์ หนิง ป๊อบ กวาง บุ๋ม ยืนประกบด้านหลังผู้เกษียณ 1:1 เพื่อช่วยรับของ</div>

    <div class="section-divider"><span>20.00 – 20.30 น. · มอบดอกไม้มุทิตาจิต / ถ่ายภาพร่วมกัน</span></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ขอเรียนเชิญผู้บริหาร ผู้ร่วมงาน และแขกผู้มีเกียรติทุกท่าน ร่วมมอบดอกไม้และแสดงมุทิตาจิตแด่ผู้เกษียณอายุราชการ พร้อมบันทึกภาพร่วมกันเป็นที่ระลึกค่ะ เชิญได้เลยค่ะ!</div></div>

    <div class="backup-box editable">🕐 <strong>Backup หากคิวมอบดอกไม้ใช้เวลานาน:</strong> "เรียนทุกท่านครับ/ค่ะ ระหว่างรอคิวมอบดอกไม้ ขอเชิญทุกท่านที่รอคิวรับประทานอาหารและพูดคุยกันไปพลาง ๆ ก่อนได้เลยนะครับ/คะ ทีมงานจะเชิญทุกท่านเป็นระยะ ๆ ค่ะ"</div>

    <div class="direction">📸 (ผู้ร่วมงานทยอยมอบดอกไม้และถ่ายภาพร่วมกับผู้เกษียณ)</div>

    <div class="section-divider"><span>20.30 – 22.00 น. · ช่วง "เรื่องเล่าประสบการณ์คุ้มครองผู้บริโภค"</span></div>

    <div class="note-box">🎙️ <strong>โทนการพูด:</strong> ช่วงนี้คือหัวใจของความสนุกในค่ำคืนนี้ เปลี่ยนโทนเป็นกันเอง มีมุกตลก คำถามชวนคุย และเปิดพื้นที่ให้ผู้เกษียณเล่าเรื่องสนุก ๆ (พูดคุยกันสบาย ๆ สไตล์ทอล์กโชว์)</div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">เป็นยังไงกันบ้างครับทุกท่าน อิ่มท้องอิ่มใจกันหรือยังครับ? ต่อไปนี้เราจะเปลี่ยนบรรยากาศกันสักหน่อยนะครับ</div></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ใช่ค่ะ! ช่วงต่อไปนี้จะเป็นช่วง <strong>"เรื่องเล่าประสบการณ์ดำเนินงานคุ้มครองผู้บริโภค"</strong> ที่จะพาทุกท่านย้อนไปฟังเรื่องราวสนุก ๆ ซึ้ง ๆ และฮา ๆ ตลอดเส้นทางการทำงานของพี่ ๆ ผู้เกษียณกันค่ะ</div></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">ดำเนินรายการโดย <strong>ภก.รังสรรค์ วงษ์บุญหนัก</strong> เภสัชกรเชี่ยวชาญ ซึ่งจะมาพูดคุยกับผู้เกษียณอายุราชการทั้ง 6 ท่านแบบใกล้ชิดครับ ขอเรียนเชิญขึ้นเวทีครับ</div></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ระหว่างที่พี่ ๆ พูดคุยกันบนเวที ถ้าท่านใดอยากส่งคำถามหรือส่งกำลังใจให้พี่ ๆ ผู้เกษียณสามารถยกมือหรือส่งเสียงมาได้เลยนะคะ วันนี้เราเป็นกันเองค่ะ</div></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">แอบกระซิบว่าใครมีมุกฮา ๆ เก็บไว้เล่าตอนนี้เลยนะครับ เดี๋ยวจะไม่มีโอกาสแล้ว!</div></div>

    <div class="direction">⏸️ (ผู้เกษียณ 6 ท่านนั่งพูดคุยกับผู้ดำเนินรายการแบบทอล์กโชว์ แลกเปลี่ยนเรื่องราวและความประทับใจในการทำงาน)</div>

    <div class="cue-box editable">🔧 <strong>Cue เจ้าหน้าที่:</strong> จัดเก้าอี้วงสนทนาสไตล์ทอล์กโชว์บนเวที · เตรียมไมโครโฟนไร้สายสำหรับผู้ดำเนินรายการและผู้เกษียณ · เปิดเพลงเบา ๆ คลอระหว่างการพูดคุย</div>

    <div class="backup-box editable">💬 <strong>Backup หากบทสนทนาเงียบหรือต้องกระตุ้นบรรยากาศ:</strong> โยนคำถามสนุก ๆ เช่น "ความทรงจำที่ประทับใจที่สุดในการทำงานคืออะไรคะ/ครับ" หรือ "ถ้าย้อนกลับไปเป็นเภสัชกรจบใหม่อีกครั้ง อยากบอกอะไรกับตัวเองคะ/ครับ" หรือชวนผู้ร่วมงานโหวตว่าใครมีมุกฮาที่สุด หรือชวนแต่ละโต๊ะร้องเพลง</div>

    <div class="line"><div class="speaker-tag all">ศรัณยู & ใหม่</div><div class="speech-bubble editable" style="border-color:rgba(100,100,100,0.3);">ขอบคุณพี่ ๆ ผู้เกษียณทุกท่านที่มาแบ่งปันเรื่องราวดี ๆ ในค่ำคืนนี้ค่ะ/ครับ ขอเสียงปรบมือดัง ๆ อีกครั้ง!</div></div>

    <div class="section-divider"><span>22.00 น. · ปิดพิธี</span></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">เรียนท่านรองนายแพทย์สาธารณสุขจังหวัดสมุทรปราการ ผู้บริหาร ผู้เกษียณอายุราชการ และแขกผู้มีเกียรติทุกท่านค่ะ สำหรับค่ำคืนแห่งความประทับใจของเราได้ดำเนินมาอย่างครบถ้วนแล้วค่ะ ในนามคณะผู้จัดงาน ต้องขอกราบขอบพระคุณผู้เกษียณอายุราชการทุกท่าน ที่ได้ทุ่มเทเสียสละตลอดเส้นทางการรับราชการที่ผ่านมาค่ะ</div></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">ขอขอบพระคุณผู้บริหาร แขกผู้มีเกียรติ และผู้เข้าร่วมงานทุกท่าน ที่ได้ร่วมกันสร้างค่ำคืนนี้ให้เต็มไปด้วยความสุขและความประทับใจครับ ขอให้พี่ ๆ ผู้เกษียณมีสุขภาพแข็งแรง มีความสุขในทุกวันหลังเกษียณอายุราชการนะครับ 🙏</div></div>

    <div class="line"><div class="speaker-tag all">ศรัณยู & ใหม่</div><div class="speech-bubble editable" style="border-color:rgba(100,100,100,0.3); font-size:16px;"><strong>แล้วพบกันใหม่ในภาคเช้าของวันพรุ่งนี้ค่ะ/ครับ สำหรับวันนี้ราตรีสวัสดิ์ค่ะ/ครับ 🌙</strong></div></div>
  </div><!-- /seg3 -->

  <!-- ============================================ -->
  <!-- SEGMENT 4 : DAY 2 -->
  <!-- ============================================ -->
  <div class="segment seg4 page-break" id="seg4">
    <div class="segment-header">
      <div class="segment-num">4</div>
      <div class="segment-info">
        <div class="segment-label">วันที่ 2 · 14 สิงหาคม 2569 · ภาคประชุมวิชาการ</div>
        <div class="segment-title editable">บรรยาย ประชุมกลุ่มย่อย<br>และปิดการประชุม</div>
        <div class="segment-time editable">⏰ 09.00 – 12.00 น.</div>
      </div>
    </div>

    <div class="note-box">🎙️ <strong>โทนการพูด:</strong> กลับสู่โทนเป็นทางการ สุภาพ กระชับ เช่นเดียวกับภาคเช้าของวันแรก</div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">สวัสดีค่ะทุกท่าน หวังว่าเมื่อคืนนี้ทุกท่านจะได้พักผ่อนกันอย่างเต็มที่นะคะ ขอต้อนรับเข้าสู่การประชุมวันที่ 2 ค่ะ</div></div>

    <div class="section-divider"><span>09.00 – 10.30 น. · บรรยาย: การตรวจสอบการโฆษณาที่เข้าข่ายฝ่าฝืนกฎหมายของสถานพยาบาล</span></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ลำดับแรกของวันนี้ ขอเรียนเชิญเข้าสู่การบรรยายในหัวข้อ <strong>"การตรวจสอบการโฆษณาที่เข้าข่ายกระทำฝ่าฝืนเกี่ยวกับกฎหมายโฆษณาของสถานพยาบาล ตามพระราชบัญญัติสถานพยาบาล"</strong> ค่ะ</div></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">โดยได้รับเกียรติจาก <strong>คุณอโนชา ชุมวิริยะสุขกุล</strong> นิติกรชำนาญการ เป็นวิทยากรบรรยายในหัวข้อนี้ครับ ขอเรียนเชิญวิทยากรขึ้นบรรยายครับ</div></div>

    <div class="direction">⏸️ (บรรยาย 09.00 – 10.30 น.)</div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ขอขอบพระคุณวิทยากรเป็นอย่างสูงค่ะ สำหรับความรู้ด้านกฎหมายที่จะเป็นประโยชน์ต่อการทำงานตรวจสอบและกำกับดูแลของทุกท่านค่ะ</div></div>

    <div class="section-divider"><span>10.30 – 11.00 น. · ประชุมกลุ่มย่อยตามเขตสุขภาพ</span></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">ต่อไปในเวลา 10.30–11.00 น. ขอเชิญทุกท่านแบ่งกลุ่มย่อยออกเป็น 3 กลุ่ม ตามเขตสุขภาพ ได้แก่ เขต 4 เขต 5 และเขต 6 ครับ เพื่อร่วมกันพิจารณาปัญหาด้านงานคุ้มครองผู้บริโภค คบส. ในพื้นที่ภาคกลาง โดยมีหัวหน้ากลุ่มงานคุ้มครองผู้บริโภคฯ ของแต่ละจังหวัดในเขต เป็นผู้นำกลุ่มย่อยตามที่เจ้าหน้าที่แจ้งครับ</div></div>

    <div class="cue-box editable">🔧 <strong>Cue เจ้าหน้าที่:</strong> จัดโต๊ะ/มุมห้องสำหรับแต่ละกลุ่มย่อยทั้ง 3 กลุ่ม · แจกกระดาษ/แบบฟอร์มสรุปประเด็นให้แต่ละกลุ่ม</div>

    <div class="direction">⏸️ (แบ่งกลุ่มย่อยตามเขตสุขภาพ ประชุมกลุ่ม 10.30–11.00 น.)</div>

    <div class="section-divider"><span>11.00 – 11.30 น. · นำเสนอผลการประชุมกลุ่มย่อย</span></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">ต่อไปขอเชิญตัวแทนแต่ละเขตนำเสนอผลการหารือค่ะ เริ่มจากเขตสุขภาพที่ 4 นำเสนอปัญหาสำคัญและผลการดำเนินงานในปีงบประมาณ 2569 ค่ะ ขอเรียนเชิญค่ะ</div></div>

    <div class="direction">⏸️ (เขต 4 นำเสนอ)</div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">ขอบคุณครับ ต่อไปขอเชิญเขตสุขภาพที่ 5 นำเสนอในลำดับต่อไปครับ</div></div>

    <div class="direction">⏸️ (เขต 5 นำเสนอ)</div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">และปิดท้ายด้วยเขตสุขภาพที่ 6 นำเสนอเป็นลำดับสุดท้ายค่ะ ขอเรียนเชิญค่ะ</div></div>

    <div class="direction">⏸️ (เขต 6 นำเสนอ)</div>

    <div class="section-divider"><span>11.30 – 12.00 น. · ซักถามและให้ข้อเสนอแนะเพิ่มเติม</span></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">ขอบคุณตัวแทนทั้ง 3 เขตสุขภาพครับ ต่อไปขอเปิดโอกาสให้ทุกท่านซักถามและให้ข้อเสนอแนะเพิ่มเติมต่อผลการนำเสนอครับ เชิญได้เลยครับ</div></div>

    <div class="direction">⏸️ (ช่วงซักถาม/ข้อเสนอแนะ)</div>

    <div class="section-divider"><span>12.00 น. · ปิดการประชุม</span></div>

    <div class="line"><div class="speaker-tag mc1-tag">ใหม่</div><div class="speech-bubble mc1-bubble editable">และแล้วเราก็เดินทางมาถึงช่วงสุดท้ายของการประชุมในครั้งนี้แล้วนะคะ ตลอด 2 วันที่ผ่านมา เราได้ร่วมกันแลกเปลี่ยนความรู้ ประสบการณ์ และสร้างเครือข่ายที่เข้มแข็งให้กับงานคุ้มครองผู้บริโภคด้านผลิตภัณฑ์สุขภาพในเขตสุขภาพกลุ่มจังหวัดภาคกลางค่ะ</div></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">ในนามคณะผู้จัดงาน ผมและพี่ใหม่ขอกราบขอบพระคุณท่านวิทยากรทุกท่าน ผู้ร่วมอภิปรายทุกท่าน ผู้บริหาร และผู้เข้าร่วมประชุมทุกท่าน ที่ให้ความร่วมมือเป็นอย่างดีตลอดทั้ง 2 วันครับ ขอปิดการประชุมเชิงปฏิบัติการโครงการพัฒนาสมรรถนะเครือข่ายคุ้มครองผู้บริโภค ด้านผลิตภัณฑ์สุขภาพ เขตสุขภาพกลุ่มจังหวัดภาคกลาง ประจำปีงบประมาณ 2569 ณ บัดนี้ครับ</div></div>

    <div class="line"><div class="speaker-tag all">ศรัณยู & ใหม่</div><div class="speech-bubble editable" style="border-color:rgba(100,100,100,0.3); font-size:16px;"><strong>ขอกราบขอบพระคุณทุกท่านอีกครั้งค่ะ/ครับ สวัสดีค่ะ/ครับ 🙏</strong></div></div>

    <div class="line"><div class="speaker-tag mc2-tag">ศรัณยู</div><div class="speech-bubble mc2-bubble editable">ขอเรียนเชิญทุกท่านรับประทานอาหารกลางวันร่วมกันก่อนเดินทางกลับโดยสวัสดิภาพครับ ขอบคุณครับ</div></div>

    <div class="direction">🍽️ (รับประทานอาหารกลางวันร่วมกัน 12.00 – 13.00 น. — จบภารกิจ)</div>
  </div><!-- /seg4 -->

  <!-- ============================================ -->
  <!-- APPENDIX -->
  <!-- ============================================ -->
  <div class="appendix">
    <h3>📖 ภาคผนวก — ทำเนียบผู้ร่วมอภิปราย / วิทยากร</h3>

    <h3 style="font-size:15px; margin-top:16px;">ผู้เกษียณอายุราชการ ประจำปี 2569 (6 ท่าน)</h3>
    <table>
      <tr><th>ลำดับ</th><th>ชื่อ-สกุล</th><th>ตำแหน่ง</th><th>หน่วยงาน</th></tr>
      <tr><td>1</td><td>ภก.ดร.สุชาติ จองประเสริฐ</td><td>-</td><td>สำนักงานคณะกรรมการอาหารและยา</td></tr>
      <tr><td>2</td><td>ภญ.ดวงกมล นุตราวงศ์</td><td>เภสัชกรเชี่ยวชาญ</td><td>สสจ.สระบุรี</td></tr>
      <tr><td>3</td><td>ภญ.เรณู เดชมา</td><td>เภสัชกรเชี่ยวชาญ</td><td>สสจ.สิงห์บุรี</td></tr>
      <tr><td>4</td><td>ภญ.วรลักษณ์ อนันตกูล</td><td>เภสัชกรเชี่ยวชาญ</td><td>สสจ.ราชบุรี</td></tr>
      <tr><td>5</td><td>ภก.ภาณุ ศรีวรรัตน์</td><td>เภสัชกรเชี่ยวชาญ</td><td>สสจ.จันทบุรี</td></tr>
      <tr><td>6</td><td>ภญ.ปิยะวรรณ จันทรสวัสดิ์</td><td>เภสัชกรชำนาญการพิเศษ</td><td>รพ.ธัญบุรี จ.ปทุมธานี</td></tr>
    </table>
    <div class="small-note">หมายเหตุ: ภก.ประสาท ลิ่มดุลย์ ข้าราชการบำนาญ นั่งเป็น VIP ตั้งแต่ต้นงาน ไม่อยู่ในขบวนเปิดตัว</div>

    <h3>ผู้ร่วมอภิปราย/วิทยากร วันที่ 13 ส.ค. — ภาคเช้า (09.15 – 12.00 น.)</h3>
    <ul>
      <li>นางรุ่งดารา เนียมโภคะ เภสัชกรชำนาญการพิเศษ</li>
      <li>นางวรางคณา เทวราชสมบูรณ์ เภสัชกรชำนาญการพิเศษ</li>
      <li>ผู้ดำเนินรายการ: นางสาวเยาวนาถ ลาภานันต์ เภสัชกรชำนาญการพิเศษ (สสจ.ระยอง)</li>
    </ul>

    <h3>ภาคบ่าย (13.00 – 18.00 น.)</h3>
    <ul>
      <li>นายจีระสันต์ มีรัตน์ธนวัต ผู้แทน สสจ.ชลบุรี</li>
      <li>นายอภิชาติ ชัยวรรณ ผู้แทน ป.ป.ส.</li>
      <li>พ.ต.อ.วีระพงษ์ คล้ายทอง ผู้กำกับการ บก.ปคบ.</li>
      <li>นางสาวจริยา อัครวรัณธร ผู้แทนศูนย์วิทยาศาสตร์การแพทย์ที่ 6 ชลบุรี</li>
      <li>นายชาติชาย ตั้งทรงสุวรรณ์ ผู้แทนสำนักอาหาร อย.</li>
      <li>นายวีระศักดิ์ เหล่าตระกูล ผู้แทน สสจ.นครปฐม</li>
      <li>ผู้ดำเนินรายการ: นางสาวณัฐยาภรณ์ วงศ์บุญเกื้อกูล เภสัชกรชำนาญการพิเศษ</li>
    </ul>

    <h3>วิทยากร วันที่ 14 ส.ค.</h3>
    <ul>
      <li>นางอโนชา ชุมวิริยะสุขกุล นิติกรชำนาญการ (บรรยายเรื่องการโฆษณาสถานพยาบาล)</li>
    </ul>

    <h3>✅ Checklist สำหรับพิธีกร (ไม่อ่านออกไมโครโฟน)</h3>
    <ul>
      <li>ตรวจสอบชื่อ-ยศ-ตำแหน่งของวิทยากรและผู้ร่วมอภิปรายทุกท่านก่อนเริ่มงานทุกวัน</li>
      <li>ตรวจสอบกำหนดการล่าสุด เนื่องจากอาจมีการปรับเปลี่ยนตามความเหมาะสม</li>
      <li>ประสานทีมงานเบื้องหลัง (น้องหงส์ พี่หงษ์ น้องโย น้องโจ้ พี่เนะ พี่ตุ๊ก พี่แอร์ น้องยุ้ย น้องป๊อบ) ก่อนแต่ละช่วงกิจกรรมภาคค่ำ</li>
      <li>เตรียมไมโครโฟนสำรองทั้งสองวัน</li>
      <li>แบ่งบทให้ชัดเจนล่วงหน้าระหว่างพิธีกรทั้งสองคน โดยเฉพาะช่วงแนะนำรายชื่อผู้ร่วมอภิปรายจำนวนมาก</li>
      <li>จำโทนการพูด: ภาคประชุม = ทางการ / ภาคเลี้ยงค่ำ = เป็นกันเอง สนุกสนาน</li>
      <li>รักษาเวลาตามกำหนดการ โดยเฉพาะช่วงพักอาหารว่างและอาหารกลางวัน</li>
    </ul>
  </div>

</div><!-- /content -->

<button class="print-btn no-print" onclick="window.print()">🖨️ พิมพ์สคริปต์</button>

<script>
  let editMode = false;

  function toggleEdit() {
    editMode = !editMode;
    document.querySelectorAll('.editable').forEach(function(el) {
      el.contentEditable = editMode;
    });
    document.body.classList.toggle('edit-mode', editMode);
    const btn = document.getElementById('editBtn');
    btn.textContent = editMode ? '✅ เสร็จสิ้นการแก้ไข' : '✏️ แก้ไขข้อความ';
    btn.classList.toggle('on', editMode);
  }

  function exportHtml() {
    const clone = document.documentElement.cloneNode(true);
    clone.querySelectorAll('.editable').forEach(function(el) { el.removeAttribute('contenteditable'); });
    const toolbar = clone.querySelector('#toolbar');
    if (toolbar) toolbar.remove();
    clone.querySelector('body').classList.remove('toolbar-active', 'edit-mode');
    const htmlStr = '<!DOCTYPE html>\n' + clone.outerHTML;
    try {
      const blob = new Blob([htmlStr], { type: 'text/html' });
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url;
      a.download = 'บทพิธีกรคู่_ฉบับแก้ไข.html';
      document.body.appendChild(a);
      a.click();
      document.body.removeChild(a);
      URL.revokeObjectURL(url);
    } catch (e) {
      alert('ไม่สามารถดาวน์โหลดอัตโนมัติได้ กรุณาเปิดไฟล์นี้ในเบราว์เซอร์แยกต่างหาก แล้วลองอีกครั้ง หรือใช้ Ctrl+S เพื่อบันทึกหน้านี้');
    }
  }

  document.body.classList.add('toolbar-active');
</script>

</body>
</html>
