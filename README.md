# Store-Prosedur



//registMasyarakat
nik varchar 255
name varchar 255
email varchar 255
password varchar 255
tlp varchar 255

BEGIN
INSERT INTO userregist(nik,name,email,tlp,password) VALUES(nik,name,email,tlp,password);
END
//registMasyarakat



//tambbahPetugas
name varchar 255
email varchar 255
password varchar 255
tlp varchar 255
rolle varchar 255

BEGIN
INSERT INTO users(name,email,tlp,password,rolle) VALUES(name,email,tlp,password,rolle);
END
//tambbahPetugas



//cek status
BEGIN
SELECT COUNT(status) FROM pengaduan_15467 WHERE status='selesai';
END
//cek status
