<template>
  <div  className="container">
      <h3 className="d-flex justify-content-center">
        Stock Management. Vue JS Frontend.
      </h3>

      <nav className="navbar navbar-expand-sm bg-light navbar-dark">
          <ul className="navbar-nav">

        
            <li className="nav-item m-1">
                <router-link class="btn btn-light btn-outline-primary"
                to="/stocks">Stocks</router-link>
            </li>

            <li className="nav-item m-1">
                <router-link class="btn btn-light btn-outline-primary"
                to="/goods">Goods</router-link>
            </li>

            <li className="nav-item m-1">
                <router-link class="btn btn-light btn-outline-primary"
                to="/goodincomes">Good Reciept</router-link>
            </li>           

            <li className="nav-item m-1">
                <router-link class="btn btn-light btn-outline-primary"
                to="/goodmoves">Goods Move</router-link>
            </li>           

            <li className="nav-item m-1">
                <router-link class="btn btn-light btn-outline-primary"
                to="/goodrests">Goods Rest</router-link>
            </li>   

            <li className="nav-item m-1">
                <router-link class="btn btn-light btn-outline-primary"
                to="/">About</router-link>
            </li>            

          </ul>
      </nav>
      <router-view></router-view>
  </div>
</template>