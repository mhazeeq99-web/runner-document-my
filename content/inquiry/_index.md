---
title: "Inquiry"
description: "Hantar pertanyaan atau permohonan servis"
---

## Borang Inquiry

Sila isi maklumat di bawah. Semua pertanyaan akan saya balas.

<form
  action="https://formspree.io/f/xgoegdgl"
  method="POST"
  enctype="multipart/form-data"
>

  <label>Nama *</label><br>
  <input type="text" name="nama" required><br><br>

  <label>Nombor Telefon *</label><br>
  <input type="tel" name="telefon" required><br><br>

  <label>Email </label><br>
  <input type="email" name="email"><br><br>

  <label>Alamat Penerima </label><br>
  <textarea name="alamat" rows="4"></textarea><br><br>

  <label>Mesej / Butiran Tambahan</label><br>
  <textarea name="mesej" rows="4"></textarea><br><br>

  <!-- Anti-spam -->
  <input type="hidden" name="_subject" value="Inquiry Baru dari Website">
  <input type="hidden" name="_captcha" value="false">

  <button type="submit" style="padding: 14px 28px;
 background-color: #2563eb; color: white; border: none; border-radius: 8px; font-size: 16px; font-weight: 600; cursor: pointer;">Hantar Inquiry</button>

</form>
