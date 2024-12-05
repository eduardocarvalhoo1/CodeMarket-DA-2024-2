# História de Usuário

<table>
    <thead>
        <tr style="background-color: purple; color: white">
            <th style="border-style:solid;border-width:1px;text-align:center">ID</th>
            <th style="border-style:solid;border-width:1px;text-align:center">História de Usuário</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Critérios de Aceitação</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Prioridade</th>
            <th style="border-style:solid;border-width:1px;text-align:center">RF/RNF Relacionado</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero poder selecionar um produto.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
                <ol>
                    <li>O sistema deve exibir uma lista de produtos disponíveis para seleção.</li>
                    <li>O sistema deve permitir a visualização dos detalhes de cada produto.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF01</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero selecionar a quantidade de produtos que desejo comprar, garantindo que não exceda o estoque disponível.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
                <ol>
                    <li>O sistema deve permitir que o usuário insira ou selecione a quantidade desejada de um produto.</li>
                    <li>O sistema deve verificar se a quantidade solicitada está disponível em estoque.</li>
                    <li>Se a quantidade estiver indisponível, uma mensagem deve informar a quantidade restante disponível no estoque.</li>
                    <li>O usuário deve poder ajustar a quantidade ou remover o item antes de confirmar o carrinho.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF02</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero visualizar a quantidade de produtos disponíveis em estoque.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
                <ol>
                    <li>O sistema deve exibir a quantidade disponível de um produto após a seleção do mesmo.</li>
                    <li>O sistema deve atualizar a quantidade de estoque em tempo real caso outro usuário realize uma compra.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF03</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US04</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero organizar os produtos em subcategorias para facilitar a navegação.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
                <ol>
                    <li>O sistema deve categorizar os produtos em grupos (ex.: eletrônicos, vestuário, alimentos).</li>
                    <li>O sistema deve permitir a busca e filtro de produtos por subcategorias.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Baixa</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF04</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US05</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero escolher uma forma de pagamento para concluir minha compra.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
                <ol>
                    <li>O sistema deve exibir as opções de pagamento disponíveis (cartão de crédito, boleto, Pix, etc.).</li>
                    <li>O sistema deve validar a forma de pagamento selecionada antes de confirmar a compra.</li>
                    <li>Mensagens claras devem ser exibidas em caso de erro ou indisponibilidade da forma de pagamento.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF05</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US06</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero poder escolher entre retirar no local ou receber em casa.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
                <ol>
                    <li>O sistema deve exibir as opções "Retirar no local" ou "Receber em casa" ao finalizar o pedido.</li>
                    <li>Se o usuário escolher "Retirar no local", o sistema deve permitir selecionar uma unidade de retirada.</li>
                    <li>Se o usuário escolher "Receber em casa", o sistema deve solicitar o endereço de entrega.</li>
                    <li>O sistema deve salvar a escolha feita pelo usuário para refletir no resumo do pedido.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF06</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US07</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero poder escolher a data e hora da entrega.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
                <ol>
                    <li>O sistema deve exibir um calendário com as datas disponíveis para entrega.</li>
                    <li>O sistema deve permitir a escolha de um intervalo de horário.</li>
                    <li>O sistema deve validar se a data/hora escolhida está disponível antes de confirmar.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF07</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US08</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero informar meu endereço e verificar se a entrega pode ser realizada no local.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
                <ol>
                    <li>O sistema deve permitir o preenchimento completo do endereço, incluindo CEP, número e complementos.</li>
                    <li>O sistema deve validar o endereço informado para confirmar se está na área de cobertura.</li>
                    <li>Se o endereço for válido, uma mensagem de confirmação deve ser exibida.</li>
                    <li>Se o endereço não for atendido, uma mensagem deve informar que a entrega não está disponível para o local.</li>
                    <li>O sistema deve oferecer a opção de retirada no local caso o endereço não seja atendido.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF08</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US09</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero pesquisar um produto específico para facilitar a localização.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
                <ol>
                    <li>O sistema deve permitir a pesquisa de produtos por nome, categoria ou código.</li>
                    <li>Os resultados devem ser exibidos rapidamente e ordenados por relevância.</li>
                    <li>Deve haver a opção de filtrar os resultados da busca.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF09</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US10</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero adicionar vários produtos ao carrinho de uma só vez.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
                <ol>
                    <li>O sistema deve permitir a seleção de múltiplos produtos em uma única operação.</li>
                    <li>O sistema deve exibir um resumo dos produtos selecionados antes de adicionar ao carrinho.</li>
                    <li>Se um produto estiver indisponível, o sistema deve informar antes de finalizar a ação.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF10</td>
        </tr>
    </tbody>
</table>
