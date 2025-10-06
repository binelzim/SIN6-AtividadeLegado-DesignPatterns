# Changelog

O formato baseado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/)

## [1.0.0] - 2025-09-29
### Adicionado
- Nova funcionalidade de notificação quando um pedido é realizado

### Corrigido
- Sem correções

### Modificado
- Sem modificações

## [1.1.0] - 2025-10-06

### Adicionado
- Adicionada a interface `Notificador` para implementar o padrão Observer.

### Corrigido
- Sem correções

### Modificado
- Refatorado o `NotificacaoService` para utilizar o padrão de projeto Observer.
- As classes `EmailService`, `SmsService` e `PushService` agora implementam a interface `Notificador`.