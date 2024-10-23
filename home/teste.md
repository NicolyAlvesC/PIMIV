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
                        </form>
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
                    </div>

                </div>
               

               <div class="forms">
                    <div class="forms-1">
                        <div class="f-titulo">
                            <h1>Contato</h1>
                        </div>
                        <form id="orderForm">
                            <label for="cnpj">CNPJ:</label>
                            <input type="text" id="cnpj" name="cnpj" required>
                    
                            <label for="email">Endereço de Email:</label>
                            <input type="email" id="email" name="email" required>
                    
                            <label for="product">Escolha um produto:</label>
                            <select id="product" name="product" required>
                                <option value="verduras">VERDURAS</option>
                                <option value="legumes">LEGUMES</option>
                                <option value="frutas">FRUTAS</option>
                                <option value="outros">OUTROS</option>
                            </select>
                    
                            <label for="description">Descrição do Pedido:</label>
                            <textarea id="description" name="description" rows="4" required></textarea>
                    
                            <button type="submit">Enviar</button>
                        </form>
                    </div>