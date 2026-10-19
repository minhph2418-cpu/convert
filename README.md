# Đổi định dạng file

Web tĩnh (một file `index.html`), mọi chuyển đổi chạy ngay trên trình duyệt người dùng, không có backend.

## Deploy lên Vercel

**Cách 1: dùng CLI**
```
npm i -g vercel
cd doi-dinh-dang-vercel
vercel --prod
```

**Cách 2: dùng GitHub**
1. Đẩy thư mục này lên một repo GitHub.
2. Vào vercel.com, chọn Add New > Project, import repo.
3. Framework Preset: Other. Không cần Build Command hay Output Directory. Bấm Deploy.

## Chạy thử trên máy
```
npx serve .
```

## Thư viện (tải từ cdnjs)
pdf.js, jsPDF, mammoth, SheetJS, lamejs.
