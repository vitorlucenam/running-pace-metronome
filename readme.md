# Running Pace Metronome 🏃‍♂️

Um Progressive Web App (PWA) que transforma seu pace de corrida em um metrônomo auditivo, ajudando corredores a manter um ritmo consistente durante seus treinos.

Inspirado na ideia do [@mvcmenmendes](https://www.instagram.com/mvcmendes/) falada no podcast [Área de transferência - 436 : Liquid Dress](https://gigahertz.fm/podcasts/adt/436).

Feito 100% com IA. 

🔗 **Acesse agora**: [https://running-pace-metronome.vercel.app/](https://running-pace-metronome.vercel.app/)

## 📱 Sobre o Projeto

O Running Pace Metronome foi desenvolvido para resolver um problema comum entre corredores: manter um ritmo constante durante o treino. Ao invés de ficar olhando constantemente para o relógio, você pode simplesmente ouvir o som de pisadas sincronizadas com seu pace desejado.

### Por que usar?

- **Melhore sua consistência**: Mantenha um ritmo estável sem precisar olhar o relógio
- **Use na esteira**: Veja a conversão instantânea de pace para km/h
- **100% offline**: Funciona sem internet após o primeiro acesso

## 🚀 Funcionalidades

### Core Features
- ⏱️ **Conversão inteligente pace → cadência**: Calcula automaticamente os passos por minuto baseado no seu pace
- 🔊 **Som de pisada realista**: Áudio sintetizado que simula o som de uma pisada (não sei muito bem)
- ⏲️ **Cronômetro integrado**: Acompanhe a duração do seu treino
- 💾 **Ritmos favoritos**: Salve e acesse rapidamente seus paces mais usados
- 📱 **PWA instalável**: Adicione à tela inicial e use como um app nativo

### Interface Intuitiva
- **Input flexível**: Digite no formato MM:SS ou use números diretos (650 = 6:50)
- **Ajustes rápidos**: Botões +/- para alterar o pace em incrementos de 5 segundos
- **Feedback visual**: Indicador pulsante sincronizado com o som
- **Conversão em tempo real**: Veja instantaneamente a velocidade em km/h

### Características Técnicas
- **Range de pace**: 3:00 a 15:00 min/km (20 km/h a 4 km/h)
- **Cadência adaptativa**: 140 a 190 passos por minuto
- **Persistência de dados**: Favoritos salvos localmente
- **Wake Lock**: Mantém a tela ligada durante o uso
- **Responsivo**: Otimizado para todos os tamanhos de tela

## 📖 Como Usar

### Início Rápido
1. Acesse o app pelo navegador do seu celular
2. Ajuste o pace desejado usando os botões ou digitando diretamente
3. Toque em **INICIAR** para começar o metrônomo
4. Corra no ritmo das pisadas!

### Instalando como App
1. **Android (Chrome)**:
   - Acesse o site
   - Toque nos 3 pontos → "Adicionar à tela inicial"
   
2. **iOS (Safari)**:
   - Acesse o site
   - Toque no botão compartilhar → "Adicionar à Tela de Início"

### Dicas de Uso
- **Durante a corrida**: Use os botões +/- para ajustar sem parar o metrônomo
- **Na esteira**: Use a conversão km/h para configurar a velocidade
- **Treinos específicos**: Salve diferentes paces para fácil acesso
- **Atalhos de teclado**: Espaço (play/pause), Setas (ajustar pace)

## 🎯 Casos de Uso

### Para Corredores Iniciantes
- Aprenda a manter um ritmo constante
- Evite começar muito rápido
- Desenvolva consciência de cadência

### Para Corredores Experientes
- Treinos de tempo run precisos
- Trabalhe cadências específicas
- Mantenha ritmo em treinos longos

### Para Treinos na Esteira
- Configure rapidamente a velocidade correta
- Mantenha motivação com feedback auditivo
- Evite olhar constantemente para o display

## 🛠️ Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript Vanilla
- **PWA**: Service Worker, Web App Manifest
- **APIs Web**: Web Audio API, Wake Lock API
- **Deploy**: Vercel
- **Versionamento**: GitHub

## 🎨 Design

O app utiliza uma paleta de cores inspirada na natureza, proporcionando uma experiência visual agradável e não cansativa durante o uso:

- Verde escuro (#1C2F22, #2A5C3A) para o fundo
- Verde claro (#6BAE81, #BED996) para elementos interativos
- Tons intermediários (#A0D4AA, #538B5E) para feedback e destaques

## 🔮 Próximas Funcionalidades

- [ ] Modo intervalado (alternar entre diferentes paces)
- [ ] Funcionar em background
- [ ] Exportar dados de treino


## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/NovaFuncionalidade`)
5. Abrir um Pull Request

## 📝 Licença

Este projeto está sob licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.


---

**Desenvolvido com 💚 para a comunidade de corrida**

*Mantenha o ritmo, alcance seus objetivos!* 🏃‍♀️🏃‍♂️