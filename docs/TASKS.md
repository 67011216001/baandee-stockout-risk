# งานและผู้รับผิดชอบ (ใช้สร้าง GitHub Issues / Project board)

ผู้รับผิดชอบ: A=ข้อมูลดิบและทำความสะอาด, B=ข้อมูลแหล่งที่ 2, C=risk และ storage, D=หน้าจอ test เอกสาร (ปรับตามจริงของทีม)

- [ ] 0 นัดอาจารย์ (3 ตัวเลือกคนละวัน), สร้าง repo, แบ่งงาน — ทั้งทีม
- [ ] 1 Problem Statement → docs/problem_statement.md — ทั้งทีม
- [ ] 2 ตรวจข้อมูลดิบ → scripts/01_profile_raw.py, docs/data_quality_findings.csv — A
- [ ] 3 ตัดสินใจกฎแก้ข้อมูล → docs/decision_log.md — ทั้งทีม
- [ ] 4 ข้อมูลแหล่งที่ 2 → scripts/generate_supplier_lead_time.py, data/generated/supplier_lead_time.csv — B
- [ ] 5 ทำความสะอาด, quarantine, correction log → scripts/02_clean_data.py, data/cleaned/ — A
- [ ] 6 เชื่อมข้อมูลด้วย product_id + รายงานก่อน/หลัง → docs/join_report — A+B
- [ ] 7 ตัวคำนวณความเสี่ยง → src/risk.py — C
- [ ] 8 API (พบ / ไม่พบ / ใช้งานไม่ได้) → api/main.py, src/api_client.py — B
- [ ] 9 หน้าจอ Gradio → src/app.py — D
- [ ] 10 บันทึก/แก้ไข reorder_requests, soft delete → src/storage.py — C
- [ ] 11 tests ≥ 5 ข้อ (input/expected/actual/pass-fail) → tests/ — D + ทุกคน
- [ ] 12 README, AI_USE.md, .env.example, requirements.txt, บทบาทสมาชิก — D + ทุกคน
- [ ] 13 ตรวจ repo ไม่มี secret/.env/venv/log และสลับกันลองติดตั้งใหม่จากศูนย์ — ทุกคน
- [ ] 14 สร้าง tag v1.0-final — ผู้ดูแล repo
- [ ] 15 ซ้อม demo 8 นาที + ซ้อมตอบเรื่องส่วนของกันและกัน — ทั้งทีม
