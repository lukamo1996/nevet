<template>
  <footer class="page-footer" style="/*content: none;*/padding-top: 0;font-family: Lato, sans-serif;background: rgb(245, 245, 245);border-width: 1px;border-top-style: solid;border-top-color: rgba(202,202,202,0.41); padding-top: 0px;">
        <div class="container">
            <div class="row d-xl-flex justify-content-center justify-content-xl-center" style="padding-bottom: 10px;border-radius: 0px;border-top-width: 0px;border-top-color: var(--red);">
                <div class="col-6 px-2 col-sm-3 d-flex justify-content-center" style="font-family: Lato, sans-serif;">
                    <div class="flex-column" style="text-align: left;">
                        <h5 style="font-family: Lato, sans-serif;">Info</h5>
                        <ul style="/*list-style-type: none !important;*/">
                            <li><router-link class = "hitLinks" to="/om">Hva er dette?</router-link></li>
                            <li><router-link class = "hitLinks" to="/kontakt">Kontakt</router-link></li>
                            <li><router-link class = "hitLinks" to="/retningslinjer">Retningslinjer</router-link></li>
                        </ul>
                    </div>
                </div>
                <div class="col-6 px-2 col-sm-3 text-left d-flex justify-content-center" style="font-family: Lato, sans-serif;">
                    <div class="text-nowrap">
                        <h5>Hurtiglenker</h5>
                        <ul>
                            <li><router-link class = "hitLinks" to="/login">Logg inn</router-link></li>
                            <li><router-link class = "hitLinks" to="/blimedlem">Bli medlem</router-link></li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="row row-cols-1 justify-content-center align-items-center" style="height: 50px;">
                <div class="col-11 col-sm-7 col-md-6 col-lg-5 col-xl-5 d-flex d-lg-flex justify-content-center align-items-center align-content-center justify-content-lg-center" style="height: 50px;border-top: 1px solid rgba(119,119,119,0.11) ;">
                    <p style="color:#53595f; font-family: Lato, sans-serif;font-weight: 900;letter-spacing: 2px;font-size: 10px;margin-bottom: 0px;">© UTVIKLET AV <router-link class="hitLinks" to="/bruker/Kyrgios">SKJØNNHETEN</router-link>&nbsp;OG
                    <router-link class="hitLinks" to="/bruker/martin">UDYRET</router-link><br></p>
                </div>
            </div>
        </div>
    </footer>
</template>
