# Demo Keycloak

Project ini merupakan contoh implementasi **Keycloak** sebagai Identity and Access Management (IAM) untuk mengelola autentikasi dan otorisasi pada aplikasi.

## 📌 Fitur Utama

- Single Sign-On (SSO)
- Manajemen user dan role
- Integrasi dengan aplikasi berbasis web
- Authentication menggunakan OpenID Connect / OAuth 2.0
- Proteksi endpoint API

## 🛠️ Teknologi yang Digunakan

- Keycloak
- Docker (opsional)
- Backend (contoh: Node.js / Spring Boot)
- Frontend (opsional: React / Vue)

## 🚀 Cara Menjalankan

### 1. Jalankan Keycloak (Docker)

```bash
docker run -p 8080:8080 \
-e KEYCLOAK_ADMIN=admin \
-e KEYCLOAK_ADMIN_PASSWORD=admin \
quay.io/keycloak/keycloak:latest start-dev
