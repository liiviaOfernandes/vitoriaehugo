# Vitória & Hugo — versão corrigida

## Correções desta versão
- Corrigido o erro `Uncaught ReferenceError: abrir is not defined`.
- O popup de RSVP agora usa referências explícitas aos elementos (`abrirRSVP`, `popupRSVP`, botão fechar e formulário).
- Removida a dependência externa do Font Awesome para evitar avisos de Tracking Prevention no Edge.
- Ícones essenciais agora são renderizados localmente por CSS.
- O gerador de QR Code mantém fallback por CDN (jsDelivr / unpkg).
- Pix configurado para a chave `+5534999848413`.

## Cartão de crédito
No `index.html`, procure por:

```js
const CARTAO_CONFIG = {
    link: ""
};
```

Cole ali um link de pagamento real quando ele estiver disponível.
