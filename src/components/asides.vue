<template>


    <!-- Main Sidebar Container -->
    <aside class="main-sidebar sidebar-dark-primary elevation-4">
      <!-- Brand Logo -->
      <a href="" class="brand-link">
        <img src="dist/img/AdminLTELogo.png"
             alt="AdminLTE Logo"
             class="brand-image img-circle elevation-3"
             style="opacity: .8">
        <span class="brand-text font-weight-light">AdminLTE 3</span>
      </a>

      <!-- Sidebar -->
      <div class="sidebar">
        <!-- Sidebar user (optional) -->
        <div class="user-panel mt-3 pb-3 mb-3 d-flex">
          <div class="image">
            <img src="dist/img/user2-160x160.jpg" class="img-circle elevation-2" alt="User Image">
          </div>
          <div class="info">
            <a href="#" class="d-block">Alexander Pierce</a>
          </div>
        </div>

        <!-- Sidebar Menu -->
          <nav class="mt-2">
            <ul class="nav nav-pills nav-sidebar flex-column" data-widget="treeview" role="menu" data-accordion="false">
              <!-- Add icons to the links using the .nav-icon class
                   with font-awesome or any other icon font library -->



              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-user"></i>
                  <p>
                    Clientes
                    <i class="right fas fa-angle-left"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                  <a href="clientes" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Clientes</p>
                    </a>
                  </li>


                </ul>
              </li>
              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-truck"></i>
                  <p>
                    Proveedores
                    <i class="fas fa-angle-left right"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                    <a href="pages/UI/ribbons.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Proveedores</p>
                    </a>
                  </li>
                </ul>
              </li>

              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-users"></i>
                  <p>
                    Empleados
                    <i class="fas fa-angle-left right"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                    <a href="pages/forms/general.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Empleados</p>
                    </a>
                  </li>
                </ul>
              </li>

              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-warehouse"></i>
                  <p>
                    Ubicaciones
                    <i class="fas fa-angle-left right"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                    <a href="pages/tables/simple.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Ubicaciones</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/tables/data.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Estantes</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/tables/jsgrid.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Asignación</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/tables/jsgrid.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Movimientos</p>
                    </a>
                  </li>
                </ul>
              </li>

              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-box-open"></i>
                  <p>
                    Productos
                    <i class="fas fa-angle-left right"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                    <a href="pages/tables/simple.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Productos</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/tables/data.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Categorias</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/tables/jsgrid.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Presentaciones</p>
                    </a>
                  </li>
                </ul>
              </li>


              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-shopping-cart"></i>
                  <p>
                    Compras
                    <i class="fas fa-angle-left right"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                    <a href="pages/mailbox/mailbox.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Compras</p>
                    </a>
                  </li>
                </ul>
              </li>

              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-table"></i>
                  <p>
                    Inventario
                    <i class="fas fa-angle-left right"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                    <a href="pages/tables/simple.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Cargas de inventario</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/tables/data.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Descargos de inventario</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/tables/jsgrid.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Consultar Stock</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/tables/jsgrid.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Ajuste de Inventario</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/tables/jsgrid.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Ajuste</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/tables/jsgrid.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Administrar Lotes</p>
                    </a>
                  </li>
                </ul>
              </li>

              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-money-check-alt"></i>
                  <p>
                    Facturacion
                    <i class="fas fa-angle-left right"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                    <a href="pages/examples/invoice.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Venta</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/profile.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Pre Venta</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/e_commerce.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Facturas</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/projects.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Facturas Pendientes</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/project_add.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Devoluciones</p>
                    </a>
                  </li>
                </ul>
              </li>

              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-piggy-bank"></i>
                  <p>
                    Bancos
                    <i class="fas fa-angle-left right"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Bancos</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/register.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Movimientos</p>
                    </a>
                  </li>
                </ul>
              </li>

              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-hand-holding-usd"></i>
                  <p>
                    Cuentas Por Cobrar
                    <i class="fas fa-angle-left right"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Creditos</p>
                    </a>
                  </li>
                </ul>
              </li>

              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-money-bill-alt"></i>
                  <p>
                    Cuentas Por Pagar
                    <i class="fas fa-angle-left right"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Pagos</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Generar Pagos</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Cuentas por Pagar</p>
                    </a>
                  </li>
                </ul>
              </li>

              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-cash-register"></i>
                  <p>
                    Caja
                    <i class="fas fa-angle-left right"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Corte</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Caja</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Movimiento Caja</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Resumen de vales</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Apertura de Caja</p>
                    </a>
                  </li>
                </ul>
              </li>

              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-file-alt"></i>
                  <p>
                    Cotizaciones
                    <i class="fas fa-angle-left right"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Cotizaciones</p>
                    </a>
                  </li>
                </ul>
              </li>

              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-shopping-bag"></i>
                  <p>
                    Pedidos
                    <i class="fas fa-angle-left right"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Pedidos</p>
                    </a>
                  </li>
                </ul>
              </li>

              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-file-pdf"></i>
                  <p>
                    Reportes
                    <i class="fas fa-angle-left right"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Hoja de Conteo</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Kardex</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Inventario</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Libro de Compras</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Kardex General</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Ventas a Contribuyentes</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Ventas a Consumidores</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Reporte Fiscal</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Reporte de Utilidades</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Reporte de Reposición</p>
                    </a>
                  </li>
                </ul>
              </li>

              <li class="nav-item has-treeview">
                <a href="#" class="nav-link">
                  <i class="nav-icon fas fa-cogs"></i>
                  <p>
                    Configuraciones
                    <i class="fas fa-angle-left right"></i>
                  </p>
                </a>
                <ul class="nav nav-treeview">
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin usuarios</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Admin Empresa</p>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="pages/examples/login.html" class="nav-link">
                      <i class="far fa-circle nav-icon"></i>
                      <p>Back-up</p>
                    </a>
                  </li>
                </ul>
              </li>


            </ul>
          </nav>
          <!-- /.sidebar-menu -->
      </div>
      <!-- /.sidebar -->
    </aside>



</template>

<script>

  export default {
    name: 'AsideComponent',
    props: {
      msg: String
    }
  }

</script>
