# Hyperlink

> digunakan untuk membuat teks ketika diklik akan menuju suatu halaman website

```
<a href="https://www.google.com">Google</a>
```

## atributes

### target

> digunakan untuk mendefisinikan dimana halaman akan dibuka

- \_self digunakan sebagai default/ tab yang sedang digunakan
- \_blank digunakan untuk tab baru

```
<a href="./" target="_blank"></a>
```

### title

> digunakan untuk menampilkan title pada link

```
<a href="./" title="Ini adalah title">Title</a>
```

## relative url dan absolute url

### relative

> digunakan untuk menuju suatu halaman lain dari sebuah domain

```
<a href="https://www.google.com">Google</a>
```

### absolute

> digunakan untuk domain / halaman yang sama

- ./ berarti folder ini
- ../ berarti mundur 1 folder
- ../../ berarti mundur 2 folder

```
<a href="../nama-file.html">file</a>
```

# link ke email dan telephone

```
<a href="mailto:example@email.com">Email</a>
<a href="tel:+82319823102938">telepone</a>
```

## bormark url

> digunakan untuk menuju suatubagian pada halaman yang sedang digunakan

```

<a href="#bagian1">Ke bagian 1</a>
...
<h1 id="bagian1">Ini Suatu bagia</h1>
```
