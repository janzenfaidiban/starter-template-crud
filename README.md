# Starter Template CRUD

## Demos

[Template CRUD - HTML Only](https://janzenfaidiban.github.io/starter-template-crud/template-crud/)

[Template CRUD - HTML + Tailwind + Font Awesome](https://janzenfaidiban.github.io/starter-template-crud/template-crud-tailwind/)

## Instal Tailwind CSS

Pasang link CDN Tailwind CSS di bagian ```<head>...</head>```

```html
<!-- Tailwind CSS -->
<script src="https://cdn.tailwindcss.com"></script>
```

## Instal Font Awesome Icons

Pasang link Font Awesome Icon CSS di bagian ```<head>...</head>```

```html
<!-- Font Awesome Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css" integrity="sha512-1sCRPdkRXhBV2PBLUdRb4tMg1w2YPf37qatUFeS7zlBy7jJI8Lf4VHwWfZZfpXtYSLy85pkm9GaYVYMfw5BC1A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
```

## Buat tombol dengan Tailwind CSS dan Font Awesome

```html
<a href="read.html" class="bg-blue-900 text-white py-2 px-3 rounded shadow mr-2">
    <i class="fa-solid fa-users mr-1"></i>
    Users
</a>
```