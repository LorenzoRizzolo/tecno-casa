<Page name="home" id="home">

  <Navbar>
    <NavTitle>
      <h1 class="title">Tecnocasa</h1>
    </NavTitle>
    <NavRight>
      <img class="logo" src="tecnocasa.png" alt="lg">
    </NavRight>
  </Navbar>

  <center>
    <Card expandable>
      <CardContent bgColor="red" padding={false}>
        <div class="card-red" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
              <Icon f7="exclamationmark_triangle" />
              <Icon f7="checkmark_shield" />
              <Icon f7="delete_right" /><br>
              Informazioni sulle case<br>
              <small style="opacity: 0.7">Visualizza tutte le informazioni sull'acquisto e vendita delle case.</small>
              <Button class="open-popup" fill popupOpen=".demo-popup">Contatti</Button>
              <Popup class="demo-popup" opened={popupOpened} onPopupClosed={() => popupOpened = false}>
                <Page>
                  <Navbar title="Contatti">
                    <NavRight>
                      <Link popupClose>Chiudi</Link>
                    </NavRight>
                  </Navbar>
                  <Block>
                    <b>Nome: </b>Mancu Maverick <br>
                    <b>Email: </b>@lolloriz#7142 <br>
                    <b>Telefono: </b>553212509 <br>
                    <b>Civico Tecnocasa (temporaneo): </b>692
                  </Block>
                </Page>
              </Popup>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <h3>Avvisi</h3>
          <nav>
            <p> <Icon f7="exclamationmark_triangle" /> Ogni casa può essere comprata. </p>
            <p> <Icon f7="exclamationmark_triangle" /> I prezzi sono trattabili solo per le case create sul momento. </p>
            <p> <Icon f7="exclamationmark_triangle" /> Tecnocasa guadagna solo il 5% sulla vendita della casa. </p>
            <p> <Icon f7="exclamationmark_triangle" /> Se un cittadino dovesse comprare una casa senza il permesso di Tecnocasa, tale casa verrà rimossa al cittadino, a me no che non venga a dichiarare un errore o tale acquisto. </p>
            <p> <Icon f7="exclamationmark_triangle" /> Le case vendute non sono arredate, ogni cittadino potrà arredare la propria casa tranquillamente una volta comprata.</p>
          </nav>
          <h3>Cose che puoi fare</h3>
          <nav>
            <p><Icon f7="checkmark_shield" /> Visitare le case.</p>
            <p><Icon f7="checkmark_shield" /> Chiamare un dipendete di Tecnocasa per una casa personalizzata.</p>
            <p><Icon f7="checkmark_shield" /> Scegliere una casa a proprio piacimento, successivamente creata da un dipendete Tecnocasa.</p>
            <p><Icon f7="checkmark_shield" /> Arredare la propria casa.</p>
          </nav>
          <h3>Cose che non puoi fare</h3>
          <nav>
            <p><Icon f7="delete_right" /> Vendere una casa da solo, aspetta sempre un dipendete di Tecnocasa.</p>
            <p><Icon f7="delete_right" /> Comprare una casa in completa autonomia.</p>
          </nav>
        </div>
      </CardContent>
    </Card>

    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Civico 543 <br>
            <small>Casa - <b>Libera</b></small><br>
            <small style="opacity: 0.7">Lussuosa <br> <i>Prezzo: </i></small><b>1.815.000 </b>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <img class="casa" src="case/543.jpg" alt="c.543"><br>
          Bellissima casa leggermente fuori città, isolata, per goderti il piacere della tua giornata.
          Completa di piscina e zona ospiti. 
        </div>
      </CardContent>
    </Card>
  
    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Civico 835<br>
            <small>Casa - <b>Libera</b></small> <br>
            <small style="opacity: 0.7">Lussuosa <br> <i>Prezzo: </i></small><b>1.815.000 </b>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <img class="casa" src="case/835.jpg" alt="c.543">  <br>
          Villa spaziosa completa di piscina, giardino, entrata lussuosa, terrazzo. Situata in una zona tranquilla della città, verso nord-ovest.
        </div>
      </CardContent>
    </Card>
  
    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Civico 618<br>
            <small>Casa - <b>Libera</b></small> <br>
            <small style="opacity: 0.7">Lussuosa <br> <i>Prezzo: </i></small><b>1.936.000 </b>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <img class="casa" src="case/618.png" alt="c.543"><br>
          Lussuosissima casa fuori città. 
        </div>
      </CardContent>
    </Card>

    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Civico 333<br>
            <small>Appartamento - <b>Libero</b></small> <br>
            <small style="opacity: 0.7">Ufficio / Desposito <br> <i>Prezzo: </i></small><b> 484.000 </b>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <img class="casa" src="case/333.jpg" alt="c.543"> <br>
          Loft vicino al mare, Arredato da ufficio per gli uomini d'affare. 
        </div>
      </CardContent>
    </Card>

    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Civico 538<br>
            <small>Appartamento - <b>Libero</b></small> <br>
            <small style="opacity: 0.7">Rustico <br> <i>Prezzo: </i></small><b> 181.500 </b>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <img class="casa" src="case/538.jpg" alt="c.543"> <br>
          Appartamento rustico, caratteristico per il suo stile all'interno come se fosse un bar. 
        </div>
      </CardContent>
    </Card>

    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Civico 538<br>
            <small>Appartamento - <b>Libero</b></small> <br>
            <small style="opacity: 0.7">Bellino <br> <i>Prezzo: </i></small><b> 242.000</b>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <img class="casa" src="case/538.jpg" alt="c.543"> <br>
          Appartamento centrale, ben situato come posizione e spazioso all'interno. Appartamento di classe a basso prezzo ! 
        </div>
      </CardContent>
    </Card>

    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Civico 850<br>
            <small>Casa - <b>Libera</b></small> <br>
            <small style="opacity: 0.7">Lussuosa <br> <i>Prezzo: </i></small><b>1.778.000 </b>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <img class="casa" src="case/850.png" alt="c.543"><br>
          Villa lussuosa dotata di piscina, molto spaziosa.
        </div>
      </CardContent>
    </Card>

    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Civico 878<br>
            <small>Casa - <b>Libera</b></small> <br>
            <small style="opacity: 0.7">Lussuosa <br> <i>Prezzo: </i></small><b>1.185.000 </b>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <img class="casa" src="case/878.png" alt="c.543"><br>
          Villa lussuosa.
        </div>
      </CardContent>
    </Card>

    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Civico 705<br>
            <small>Casa - <b>Libera</b></small> <br>
            <small style="opacity: 0.7">Lussuosa <br> <i>Prezzo: </i></small><b>1.694.000 </b>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <img class="casa" src="case/705.png" alt="c.543"><br>
          Villa lussuosa.
        </div>
      </CardContent>
    </Card>

    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Civico 550<br>
            <small>Casa - <b>Libera</b></small> <br>
            <small style="opacity: 0.7">Lussuosa <br> <i>Prezzo: </i></small><b>1.452.000 </b>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <img class="casa" src="case/550.jpg" alt="c.543">  <br>
          Lussuosa villa fuori città. IMPERDIBILE !!
        </div>
      </CardContent>
    </Card>

    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Civico 910<br>
            <small>Casa - <b>Libera</b></small> <br>
            <small style="opacity: 0.7">Lussuosissima <br> <i>Prezzo: </i></small><b>2.420.000 </b>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <img class="casa" src="case/910.jpg" alt="c.543">  <br>
          Lussuosissima casa fuori città, al confine con il deserto. 
        </div>
      </CardContent>
    </Card>

    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Civico 542<br>
            <small>Casa - <b>Libera</b></small> <br>
            <small style="opacity: 0.7">Lussuosa <br> <i>Prezzo: </i></small><b>1.210.000 </b>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <img class="casa" src="case/542.png" alt="c.543"><br>
          Villa leggermente fuori città, moderna e molto accogliente.
        </div>
      </CardContent>
    </Card>

    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Civico 847<br>
            <small>Casa - <b>Libera</b></small> <br>
            <small style="opacity: 0.7">Lussuosa <br> <i>Prezzo: </i></small><b>1.210.000 </b>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <img class="casa" src="case/847.jpg" alt="c.543">  <br>
          Villa in città con una bellissima vista.
        </div>
      </CardContent>
    </Card>

    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Civico 519<br>
            <small>Locale / Loft - <b>Libera</b></small> <br>
            <small style="opacity: 0.7">Lussuoso <br> <i>Prezzo: </i></small><b>1.210.000 </b>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <img class="casa" src="case/519.png" alt="c.543"><br>
          Lussuoso loft in centro con musica e molte stanze !
        </div>
      </CardContent>
    </Card>
  </center>
  
</Page>


<script>
  
  import {
    Accordion, 
    AccordionItem, 
    AccordionContent,
    Icon,
    Card,
    CardContent,
    CardHeader,
    Page,
    Navbar,
    NavLeft,
    NavTitle,
    NavTitleLarge,
    NavRight,
    Link,
    Toolbar,
    Block,
    BlockTitle,
    List,
    ListItem,
    Row,
    Col,
    Button, 
    Popup,
    theme, 
    TreeviewItem, 
    Treeview,
    Subnavbar, 
    Searchbar, 
    Menu, 
    MenuItem 
  } from 'framework7-svelte';

  let popupOpened = false;

  export let f7route, f7router; // just to remove debug message
</script>