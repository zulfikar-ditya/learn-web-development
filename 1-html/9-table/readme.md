# table

> digunakan untuk menampilkan data dengan format table

```
<table>
    <thead>
        <tr>
            <th>Id</th>
            <th>Nama</th>
            <th>Kelas</th>
            <th>Jurusan</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Zulfikar</td>
            <td>X</td>
            <td>RPL</td>
        </tr>

        <tr>
            <td>2</td>
            <td>Zulfikar</td>
            <td>X</td>
            <td>RPL</td>
        </tr>

        <tr>
            <td>3</td>
            <td>Zulfikar</td>
            <td>X</td>
            <td>RPL</td>
        </tr>

        <tr>
            <td>4</td>
            <td>Zulfikar</td>
            <td>X</td>
            <td>RPL</td>
        </tr>

        <tr>
            <td>5</td>
            <td>Zulfikar</td>`
            <td>X</td>`
            <td>RPL</td>
        </tr>
    </tbody>
</table>
```

## penjelasan

```
tag table digunakan untuk mendefinisikan table
tag thead digunakan untuk membuat table heading
tag tbody digunakan untuk membuat table body
tag tr digunakan untuk membuat table row
tag th digunakan untuk membuat table heading/ table data dengan bold
tag td digunakan untuk membuat table data
```

## caption

> digunakan untuk membuat judul table

```
<caption>
    Title table
</caption>
```

## rowspan colspan

### row span

> digunakan untuk membuat row blank

```
<table style="width:100%">
  <tr>
    <th>Name:</th>
    <td>Zulfikar</td>
  </tr>
  <tr>
    <th rowspan="2">Phone:</th>
    <td>1938120938123</td>
  </tr>
  <tr>
    <td>123123123</td>
  </tr>
</table>
```

### colspan

> digunakan untuk membuat kolom blank pada kolom

```
<table style="width:100%">
  <tr>
    <th>Name</th>
    <th colspan="2">Telephone</th>
  </tr>
  <tr>
    <td>Zulfikar</td>
    <td>13212983</td>
    <td>13212983</td>
  </tr>
</table>
```
