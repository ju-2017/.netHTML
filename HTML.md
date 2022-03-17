# .netHTML

        <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
            <div class="container">
                <a class="navbar-brand" asp-area="Cliente" asp-controller="Home" asp-action="Index">Practica2</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarColor01" aria-controls="navbarColor01"
                        aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarColor01">
                    <ul class="navbar-nav me-auto">
                        <li class="nav-item dropdown">
                            <a href="#" class="nav-link dropdown-toggle text-white" id="navbarDropDown" role="button" data-toggle="dropdown"
                               aria-haspopup="true" aria-expanded="false">Contenidos</a>
                            <div class="dropdown-menu" aria-labelledby="navbarDropDown">
                                <a class="dropdown-item" asp-area="Admin" asp-controller="Categorias" asp-action="Index">Categorías</a>
                                <a class="dropdown-item" asp-area="Admin" asp-controller="Articulos" asp-action="Index">Artículos</a>
                                <a class="dropdown-item" asp-area="Admin" asp-controller="Sliders" asp-action="Index">Sliders</a>
                                <a class="dropdown-item" asp-area="Admin" asp-controller="Usuarios" asp-action="Index">Usuarios</a>
                            </div>
                    </ul>
                </div>
                <partial name="_LoginPartial" />
            </div>
        </nav>
