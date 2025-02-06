# SP-API: Amazon selling partner API
> Api usada para integração do marktplace Amazon com e-commerce
> > Documentação oficial da API [aqui](https://developer-docs.amazon.com/sp-api/docs/welcome).

## Selling Partner API Sandbox
> [Ambiente de teste da Amazon](https://developer-docs.amazon.com/sp-api/docs/the-selling-partner-api-sandbox) "A API do Parceiro de Vendas fornece dois ambientes de sandbox que permitem que você teste seus aplicativos sem afetar os dados de produção ou disparar eventos do mundo real. O sandbox estático da API do Parceiro de Vendas usa correspondência de padrões para retornar respostas estáticas e simuladas. O sandbox dinâmico da API do Parceiro de Vendas roteia solicitações para um backend de sandbox que pode retornar respostas realistas com base nos parâmetros da solicitação."
>
> Como o objetivo é testar a integração dos marktplaces com o e-commerce, a utilização do sandbox estático é sugerido, já que a diferença entre os dois é unicamente os seus valores, sendo o sandbox estático focado em apenas confirmar o funcionamento da API, com testes mais rápidos e sem depender de dados dinâmicos. Portanto utilizarei o sandbox estático, mas em alguns casos de teste utilizarei o dinamico para simular o ambiente de produção e as situações reais.
>
> A utilização dos sandobox é fundamental para evitar enviar o sistema para o ambiente de produção sem ter a total garantia de integração da SP-API com a API do e-commerce.