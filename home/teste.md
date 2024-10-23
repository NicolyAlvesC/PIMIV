<div class="forms-2">
                        <div class="f-titulo">
                            <h1>CONSULTE</h1>
                        </div>
                        <form id="consultaForm" onsubmit="consultarPedidos(event)">
                            <label for="cnpj">CNPJ:</label>
                            <input type="text" id="cnpj" name="cnpj" required>
                
                            <label for="data">Data do Pedido:</label>
                            <input type="date" id="data" name="data" required>
                
                            <button type="submit">Consultar</button>

                             <h2>Resultados da Consulta</h2>
                            <table id="tabela-pedidos" border="1">
                                <thead>
                                    <tr>
                                        <th>CNPJ</th>
                                        <th>Data do Pedido</th>
                                        <th>Produto</th>
                                        <th>Descrição</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <!-- As linhas de pedidos serão adicionadas aqui -->
                                </tbody>
                         </table>
                        </form>
                       
                    </div>

                </div>
               

               <div class="forms">
                    <div class="forms-1">
                                         </div>