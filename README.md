# Gerador de Assinatura de E-mail

Este projeto é uma ferramenta baseada em navegador para criar assinaturas de e-mail personalizadas. Ele permite que os usuários selecionem diferentes modelos, preencham suas informações e gerem uma assinatura em HTML que pode ser copiada para clientes de e-mail como o Outlook, ou baixada como uma imagem JPG.

## Como Usar

1.  **Abra o arquivo `assinatura.html` em seu navegador.**
2.  **Selecione o Modelo de Assinatura:**
    *   Escolha entre os modelos disponíveis no menu suspenso (por exemplo, "Servidores - DRE", "Servidores - Escola", "Setores DRE / Prédio Escola").
3.  **Preencha os Campos:**
    *   Insira suas informações nos campos do formulário correspondentes ao modelo selecionado. Campos como nome, cargo, e-mail, telefone e endereço são comuns.
4.  **Gerar Assinatura:**
    *   Clique no botão "Gerar Assinatura". A pré-visualização da sua assinatura aparecerá na parte inferior da página.
5.  **Copiar HTML:**
    *   Clique no botão "Copiar HTML". Isso copiará o código HTML da assinatura para a sua área de transferência.
    *   Cole o HTML em seu cliente de e-mail (por exemplo, nas configurações de assinatura do Outlook).
6.  **Baixar Imagem:**
    *   Clique no botão "Baixar Imagem". Isso fará o download da assinatura como um arquivo de imagem JPG.

## Funcionalidades

O gerador oferece diferentes modelos para atender a várias necessidades:

*   **Servidores - DRE:** Modelo destinado a servidores que atuam nas Diretorias Regionais de Educação (DRE).
*   **Servidores - Escola:** Modelo para servidores que trabalham em unidades escolares.
*   **Setores DRE / Prédio Escola:** Modelo para setores específicos dentro das DREs ou para o prédio da escola como um todo.

Cada modelo possui campos específicos para garantir que todas as informações relevantes sejam incluídas na assinatura.

## Tecnologias Utilizadas

*   **HTML:** Para a estrutura da página e do formulário.
*   **CSS:** Para a estilização visual dos elementos.
*   **JavaScript:** Para a lógica de funcionamento, incluindo:
    *   Alternância dinâmica dos campos do formulário com base no modelo selecionado.
    *   Validação dos dados de entrada.
    *   Geração dinâmica do HTML da assinatura.
    *   Funcionalidade de copiar para a área de transferência.
    *   Interação com a biblioteca `html2canvas`.
*   **html2canvas:** Uma biblioteca JavaScript para capturar capturas de tela de páginas da web ou partes delas, usada aqui para a funcionalidade "Baixar Imagem".

## Como Contribuir

Contribuições são bem-vindas! Se você tiver sugestões de melhorias, novos modelos ou correções de bugs:

1.  Faça um fork deste repositório.
2.  Crie uma nova branch para sua feature (`git checkout -b feature/nova-feature`).
3.  Faça commit de suas alterações (`git commit -am 'Adiciona nova feature'`).
4.  Faça push para a branch (`git push origin feature/nova-feature`).
5.  Abra um Pull Request.

## Licença

Este projeto é distribuído sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes (Nota: arquivo LICENSE não incluído neste exemplo, mas recomendado para projetos reais).
