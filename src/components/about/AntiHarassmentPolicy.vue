<template>
    <v-container class="pa-0 my-0">
        <v-layout wrap align-start justify-start row fill-height class="my-0" >

            <v-flex xs12 md8 lg8 class="pa-2 my-0">
                <p class="google-font" style="font-size:180%;color:#0277bd">Pol&iacute;tica Anti-Acoso</p>

                <p class="google-font" style="font-size:110%">
                    <b style="font-size:120%;color: #2E2E2E;">¿Por qu&eacute; tenemos una pol&iacute;tica sobre esto para {{chapterDetails.ChapterName}}?</b>
                    <ul class="mt-2" style="font-size:110%">
                        <li class="google-font">Para establecer expectativas sobre el comportamiento de los miembros de nuestra comunidad tanto en l&iacute;nea como en eventos presenciales. Simplemente tener una pol&iacute;tica contra el acoso puede evitar el acoso.</li>
                        <li class="google-font">Alienta a las personas a asistir que hayan tenido malas experiencias en otros eventos.</li>
                        <li class="google-font">Le da al personal del evento / voluntarios instrucciones sobre cómo manejar el acoso r&aacute;pidamente, con una cantidad mínima de interrupci&oacute;n para el evento.</li>
                    </ul>
                </p>

                <p class="google-font" style="font-size:110%">
                    <b style="font-size:120%;color: #2E2E2E;">Sean tolerantes los unos con los otros</b>
                    <br><br>
                    Trata a todos con respeto. Participa reconociendo que todo el mundo merece estar aquí y cada uno de nosotros tiene derecho a disfrutar de nuestra experiencia sin temor de acoso, discriminación o condescendencia, ya sea flagrante o por medio de micro-agresiones.
                </p>

                <p class="google-font" style="font-size:110%">
                    <b style="font-size:120%;color: #2E2E2E;">Si ves o escuchas algo, d&iacute;noslo</b>
                    <br><br>
                    El acoso no se tolera, y usted está facultado para comprometerse amablemente cuando usted o los demás son despreciados. Además, asuma la intención como positiva. La persona que te hace sentir incómoda puede no ser consciente de lo que están haciendo, y educadamente puedes hacerle notar su comportamiento.
                </p>

                <p class="google-font" style="font-size:110%">
                    <b style="font-size:120%;color: #2E2E2E;">Pr&aacute;ctica diciendo "S&iacute; y..." el uno al otro</b>
                    <br><br>
                    Responder a algo con un "¡NO!" o exclamando "¡no, est&aacute;s equivocado(a)!" de inmediato, no es siempre lo mejor. Construye sobre las ideas del otro. Todos nos beneficiamos cuando creamos juntos.
                </p>

                <p class="google-font" style="font-size:110%">
                    <b style="font-size:120%;color: #2E2E2E;">{{chapterDetails.ChapterName}} est&aacute; dedicado a proveer una experiencia libre de acoso para todos, no importando: </b>
                    <ul class="mt-2" style="font-size:110%">
                        <li class="google-font">Neurodiversidad</li>
                        <li class="google-font">Carrera</li>
                        <li class="google-font">Experiencia profesional</li>
                        <li class="google-font">Raza</li>
                        <li class="google-font">Nacionalidad</li>
                        <li class="google-font">G&eacute;nero</li>
                        <li class="google-font">Identidad de g&eacute;nero</li>
                        <li class="google-font">Presentaci&oacute;n de g&eacute;nero</li>
                        <li class="google-font">Orientaci&oacute;n sexual</li>
                        <li class="google-font">A&ntilde;os de Edad</li>
                        <li class="google-font">Tama&ntilde;o corporal</li>
                        <li class="google-font">Diferentes habilidades</li>
                        <li class="google-font">Apariencia</li>
                        <li class="google-font">Religi&oacute;n</li>
                        <li class="google-font">Embarazo</li>
                    </ul>
                    <span class="google-font" style="font-size:110%">La anterior no es una lista exhaustiva y podr&iaacute;a no incluir una situaci&oacute;n o conducta considerada como acoso -- no toleramos el acoso de los participantes en eventos y comunidades en l&iacute;nea de ninguna forma.</span>
                </p>
                <p class="google-font" style="font-size:120%">El lenguaje y las imágenes sexuales no son apropiadas para ningún evento, incluidas las charlas. Los participantes del evento que violen estas reglas pueden ser expulsados del evento y se les impedirá participar en futuros eventos y hasta podrían ser elminiados de participar en conversaciones en línea en los canales de la comunidad, dicha decisión queda a discreción de los(as) organizadores(as) del evento y/o de la comunidad.</p>
                <p class="google-font" style="font-size:110%">
                  <b style="font-size:120%;color: #2E2E2E;">Tenemos una POLÍTICA DE CERO TOLERANCIA por acoso de cualquier tipo, incluyendo pero no limitado a:</b>
                    <ul class="mt-2" style="font-size:110%">
                        <li class="google-font">Acecho / seguimiento</li>
                        <li class="google-font">Acosar con fotograf&iacute;a o grabaci&oacute;n</li>
                        <li class="google-font">Intimidaci&oacute;n deliberada</li>
                        <li class="google-font">Interrupci&oacute;n sostenida de las conversaciones u otros eventos</li>
                        <li class="google-font">Comentarios escritos o verbales ofensivos</li>
                        <li class="google-font">Imágenes sexuales en espacios públicos</li>
                        <li class="google-font">Contacto f&iacute;sico inapropiado</li>
                        <li class="google-font">Atenci&oacute;n sexual o física no deseada</li>
                    </ul>
                </p>

                <p class="google-font" style="font-size:120%">
                    <b style="font-size:120%;color: #2E2E2E;">Esperamos que los participantes a quienes se les llame la atenci&oacute;n a que detenan cualquier comportamiento de acoso de inmediato.</b>
                    <br><br>
                    Te damos poder y te alentamos a reportar cualquier comportamiento que haga que t&uacute; u otros se sientan inc&oacute;modos. Ac&eacute;rcate confianza a un(a) organizador(a) o voluntario(a) de la comunidad y denuncia cualquier conducta irregular. Los organizadores investigar&aacute;n la situaci&oacute;n y tomar&aacute;n las acciones apropiadas.
                    Estas acciones pueden incluir, el ayudar a los participantes agraviados a ponerse en contacto con la seguridad del local, PNC o CAM, proporcionar escoltas o, de otro modo, ayudar a que los que sufren el acoso puedan permanecer seguros durante la duración del evento.
                    <br><br>
                    Cualquier persona que se comporte de manera desordenada, incurriendo en abuso o comportamiento inc&oacute;modo, o que de otro modo no cumpla con esta pol&iacute;tica, podr&aacute; ser eliminada de cualquier evento o rechazada su admisi&oacute;n (incluso a futuros eventos de la comunidad) en cualquier momento. Las personas que sean expulsadas de un evento pagado por una violaci&oacute;n de esta pol&iacute;tica no recibir&aacute;n un reembolso.
                    <br><br>
                    De verdad esperamos nunca tener que invocar esta pol&iacute;tica y aplicarla a alguno de los miembros de nuestra comunidad, pero creemos que tener este documento ayuda a todos a pensar un poco m&aacute;s sobre c&oacute;mo nuestras acciones y palabras afectan a toda la comunidad, as&iacute; como a los indiciduos que la conforman.
                </p>

            </v-flex>

            <v-flex xs12 md4 lg4 class="pa-2 hidden-sm-and-down">

            </v-flex>
        </v-layout>

    </v-container>
</template>

<script>
import ChapterDetails from '@/assets/data/chapterDetails.json'
export default {
    data() {
        return {
            chapterDetails: ChapterDetails,
        }
    },
}
</script>
