# Tugas Lab 6 Web
## Profil
| # | Biodata |
| -------- | --- |
| **Nama** | Reza Riyaldi Irawan |
| **NIM** | 312010284 |
| **Kelas** | TI.20.A.2 |
| **Mata Kuliah** | Pemrograman Web |

## Langkah 1 `Instalasi Bootstrap`
1. Kunjungi website resmi Bootstrap di [Booststrap.com](https://getbootstrap.com).
2. Download boostrap atau menggunakan CDN untuk memasang bootstrap, _disini saya akan mendownload_.
3. Ekstrak file bootstrap yang sudah di download tadi, pindahkan folder css dan js ke dalam folder project `Lab6Web`.
4. Buat file html dengan nama `index.html`.
5. Tambahkan kode struktur dasar html.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana</title>
</head>
<body>
    
</body>
</html>
```

6. Kemudian tambahkan bootstrap kedalam kodingan tersebut, dengan membind file css dan js.
7. Tambahkan css bootstrap didalam tag `<head>`.

```html
<!-- Components CSS -->
<link rel="stylesheet" href="css/bootstrap.min.css">
<link rel="stylesheet" href="css/style.css">
```

8. Tambahkan js bootstrap di dalam tag `<body>` dipaling bawah sebelum penutup.

```html
<!-- Components JS-->
<script src="js/bootstrap.min.js"></script>
```

## Langkah 2 `Membuat Layout Sederhana Menggunakan Bootstrap`
1. Tambahkan kodingan didalam file `index.html` tersebut.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana</title>

    <!-- Components -->
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/style.css">
</head>

<body>

    <div class="container mt-5">
        <div class="card shadow">
            <h2 class="m-4" style="color: rgb(170, 170, 170);">Layout Sederhana</h2>
            <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
                <div class="container-fluid">
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarNav">
                        <ul class="navbar-nav">
                            <li class="nav-item">
                                <a class="nav-link my-container active" aria-current="page" href="#">Home</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link my-container" href="#">Artikel</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link my-container" href="#">About</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link my-container" href="#">Kontak</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </nav>

            <!-- Jumbotron -->
            <div class="bg-light p-4">
                <h1 class="display-4">Hello World</h1>
                <hr>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolorum dolor, accusamus officia neque
                    sapiente repellat quia nulla laboriosam tempore. Dolor, laboriosam perspiciatis! Magnam esse aliquam
                    eveniet voluptates, ratione doloribus minus quia vero excepturi distinctio non dolor, suscipit
                    doloremque expedita itaque fuga repudiandae molestias officiis nesciunt laborum numquam ab voluptas
                    magni?</p>
                <a href="#" class="btn btn-primary">Learn more</a>
            </div>

            <!-- Content -->
            <div class="row m-0 py-3">
                <div class="col-md-9">
                    <div class="row">
                        <div class="col-md-4">
                            <div class="card mb-3">
                                <div class="card-body text-center">
                                    <img src="https://dummyimage.com/120x120/f7b42e/fff.png" alt=""
                                        class="rounded-circle mb-3">
                                    <h4>Heading</h4>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos, ducimus!</p>
                                    <a href="#" class="btn btn-secondary">View Detail</a>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-4">
                            <div class="card mb-3">
                                <div class="card-body text-center">
                                    <img src="https://dummyimage.com/120x120/5ea1f2/fff.png" alt=""
                                        class="rounded-circle mb-3">
                                    <h4>Heading</h4>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos, ducimus!</p>
                                    <a href="#" class="btn btn-secondary">View Detail</a>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-4">
                            <div class="card mb-3">
                                <div class="card-body text-center">
                                    <img src="https://dummyimage.com/120x120/65f05d/fff.png" alt=""
                                        class="rounded-circle mb-3">
                                    <h4>Heading</h4>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos, ducimus!</p>
                                    <a href="#" class="btn btn-secondary">View Detail</a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card p-3 mt-4">
                        <div class="card-body">
                            <h3 class="text-dark mb-3">First Featurette Heading</h3>
                            <div class="row">
                                <div class="col-md-3"> 
                                    <img src="https://dummyimage.com/150x150/757575/fff.png" class="rounded mb-3" alt="">
                                </div>
                                <div class="col-md-9">
                                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quo atque ratione pariatur iusto. Explicabo odit corrupti illum. Numquam eligendi consectetur non odio ex maxime voluptates inventore vero voluptatem, repellat possimus. Iusto laudantium necessitatibus vero quis quo, quibusdam error saepe? Quisquam animi perspiciatis commodi rerum ducimus aliquid iusto eveniet aperiam blanditiis.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="card p-3 my-4">
                        <div class="card-body">
                            <h3 class="text-dark mb-3">First Featurette Heading</h3>
                            <div class="row">
                                <div class="col-md-9">
                                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quo atque ratione pariatur iusto. Explicabo odit corrupti illum. Numquam eligendi consectetur non odio ex maxime voluptates inventore vero voluptatem, repellat possimus. Iusto laudantium necessitatibus vero quis quo, quibusdam error saepe? Quisquam animi perspiciatis commodi rerum ducimus aliquid iusto eveniet aperiam blanditiis.</p>
                                </div>
                                <div class="col-md-3">
                                    <img src="https://dummyimage.com/150x150/757575/fff.png" class="rounded" alt="">
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
                <div class="col-md-3">
                    <div class="card border border-primary mb-3">
                        <div class="card-header bg-primary text-white fw-bold">
                            Widget Header
                        </div>
                        <ul class="list-group list-group-flush">
                            <li class="list-group-item">Widget Link</li>
                            <li class="list-group-item">Widget Link</li>
                            <li class="list-group-item">Widget Link</li>
                            <li class="list-group-item">Widget Link</li>
                        </ul>
                    </div>
                    <div class="card border border-primary">
                        <div class="card-header bg-primary text-white fw-bold">
                            Widget Header
                        </div>
                        <ul class="list-group list-group-flush">
                            <li class="list-group-item">
                                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Doloremque, vero sapiente.
                                Nesciunt minus, praesentium non molestiae deleniti laboriosam inventore numquam.
                            </li>
                        </ul>
                    </div>
                </div>
            </div>

            <footer class="bg-dark text-white p-3 text-center">&copy; 2022 - Universitas Pelita Bangsa @ Reza Riyaldi
                Irawan</footer>
        </div>
    </div>



    <script src="js/bootstrap.min.js"></script>
</body>

</html>
```

2. Maka hasilnya akan seperti berikut.

![Hasil](ss.png)