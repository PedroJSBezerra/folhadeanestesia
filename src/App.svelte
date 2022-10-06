<script>
</script>

<button on:click={() => window.print()}>IMPRIMIR</button>

<main>
  <header>
    <div class="logo">Logo da Empresa</div>
    <h1>FOLHA DE ANESTESIA</h1>
  </header>

  <table class="table table-bordered border-dark fw-bold">
     <tbody>
      <tr>
        <td colspan="4"><p>UNIDADE / SERVIÇO</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>LEITO</p><p contenteditable="true"></p></td>
        <td colspan="2"><p>N° PRONTUÁRIO</p><p contenteditable="true"></p></td>
      </tr>
      <tr>
        <td colspan="4"><p>NOME</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>IDADE</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>SEXO</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>COR</p><p contenteditable="true"></p></td>
      </tr>
      <tr>
        <td colspan="1"><p>DATA</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>PRES. ARTERIAL</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>PULSO</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>RESPIRAÇÃO</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>TEMPERATURA</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>PESO</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>ALTURA</p><p contenteditable="true"></p></td>
      </tr>
      <tr>
        <td colspan="1" rowspan="2"><p>TIPO SNAGUÍNEO</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>HEMÁCIAS</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>HEMOGLOBINA</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>HEMATÓCRITO</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>GLICEMIA</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>URÉIA</p><p contenteditable="true"></p></td>
        <td colspan="1" rowspan="2"><p>OUTROS</p><p contenteditable="true"></p></td>
      </tr>
      <tr>
        <td colspan="5"><p>URINA</p><p contenteditable="true"></p></td>
      </tr>
      <tr>
        <td colspan="5"><p>AP. RESPIRTÓRIO</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>ASMA</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>BRONQUITE</p><p contenteditable="true"></p></td>
      </tr>
      <tr>
        <td colspan="5"><p>AP. CIRCULATÓRIO</p><p contenteditable="true"></p></td>
        <td colspan="2"><p>ELETROCARDIOGRAMA</p><p contenteditable="true"></p></td>
      </tr>
      <tr>
        <td colspan="3"><p>AP. DIGESTIVO</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>DENTES</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>PESCOÇO</p><p contenteditable="true"></p></td>
        <td colspan="2"><p>AP. URINÁRIO</p><p contenteditable="true"></p></td>
      </tr>
      <tr>
        <td colspan="3"><p>ESTADO MENTAL</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>ATARAXICOS</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>CORTICOIDES</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>ALERGIA</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>HIPOTENSORES</p><p contenteditable="true"></p></td>
      </tr>
      <tr>
        <td colspan="5"><p>DIAGNÓSTICO PRÉ-OPERATÓRIO</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>ESTADO FÍSICO</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>RISCO</p><p contenteditable="true"></p></td>
      </tr>
      <tr>
        <td colspan="7"><p>ANESTESIAS ANTERIORES</p><p contenteditable="true"></p></td>
      </tr>
      <tr>
        <td colspan="3"><p>MEDICAÇÃO PRÉ ANESTÉSICA</p><p contenteditable="true"></p></td>
        <td colspan="1"><p>APLICADA ÀS</p><p contenteditable="true"></p></td>
        <td colspan="3"><p>EFEITO</p><p contenteditable="true"></p></td>
      </tr>
    </tbody>
  </table>

</main>

<style>

  main {
    max-width: 900px;
    margin: 0 auto;
  }
  header {
    display: flex;
    flex-direction: column;
  }

  header .logo {
    max-width: 25%;
  }

  header h1 {
    font-size: 1rem;
  }

  tr {
    height: .5rem;
  }

  td {
    padding: 2px 0 0 2px;
  }

  td p:nth-child(1) {
    /* position: absolute; */
    /* height: 14px; */
    font-size: .5rem;
    top: 0;
    left: 2px;
    word-break: break-all;
    margin: 0;
  }

  td p:nth-child(2) {
    font-size: 1rem;
    top: 0;
    left: 2px;
    word-break: break-all;
    margin: 0;
    font-weight: 600;
  }
</style>
