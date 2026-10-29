<p align="center">
  <img src="Assets/quarkium_logo_web.png" width="280" alt="Quarkium">
</p>

<h1 align="center">Quarkium</h1>

<p align="center">
  <strong>Seu Windows mais leve, limpo e rápido.</strong><br>
  Otimizador e debloater para Windows 10 e 11, com recomendações feitas para o hardware do seu PC.
</p>

<p align="center">
  <a href="https://github.com/Quarkium-Labs/Quarkium/releases/latest"><b>⬇ Baixar a versão mais recente</b></a>
  &nbsp;·&nbsp;
  <a href="HTTP_???"><b>Comprar a licença</b></a>
  &nbsp;·&nbsp;
  <a href="#suporte">Suporte</a>
</p>

---

## O que é o Quarkium?

O Quarkium é um programa para Windows que **analisa o seu PC e aplica otimizações sob medida**: remove o que pesa sem necessidade, limpa o que está sobrando e ajusta o sistema para o seu processador, placa de vídeo, memória e disco.

Em vez de uma lista genérica de "tweaks", ele detecta o seu hardware e **já deixa marcado o que faz sentido para o seu computador**. Você revisa, confirma e aplica. Tudo o que for possível reverter, pode ser revertido pelo próprio programa.

> **Produto pago.** O Quarkium é um software proprietário e exige uma License Key. Veja os termos em [LICENSE](LICENSE).

## O que ele faz

### Otimizações
| Recurso | Descrição |
|---|---|
| **Ajustes do Windows** | Cerca de 30 ajustes organizados por categoria: Privacidade, CPU, GPU, RAM, SSD, HDD, Rede, Serviços, Explorer e Debloat. Os recomendados para o seu hardware já vêm marcados. |
| **Debloat** | Lista os apps que vêm com o Windows, classificados como sugerido, opcional, de terceiros ou protegido. Você escolhe o que remover, com busca e filtros. Apps essenciais ficam bloqueados. |
| **Limpeza de disco** | Arquivos temporários, cache do Windows Update, cache de shaders DirectX, relatórios de erro, minidumps, Lixeira e cache de DNS. Mostra o espaço que será liberado antes de limpar. |
| **Liberar RAM** | Libera memória sob demanda com um clique. |
| **Programas de inicialização** | Liga e desliga o que abre junto com o Windows, de forma reversível. |
| **Ponto de restauração** | Cria um ponto de restauração do Windows antes de você aplicar mudanças. |

### Quarkium Speed
| Recurso | Descrição |
|---|---|
| **RAM automática** | Limpa a memória sozinho, por limite de uso ou por intervalo de tempo, com as regras que você definir. |
| **Modo Jogo** | Coloca o Windows em modo desempenho: plano de energia, efeitos visuais reduzidos, Game Mode do Windows, gravação em segundo plano desligada e, se você quiser, RAM liberada e processos encerrados. Tudo configurável. Ao desativar, o Windows volta ao estado original, mesmo que você tenha fechado o Quarkium. |
| **Limpeza profunda** | Examina o disco e mostra uma árvore de pastas ordenada por tamanho, para você achar o que está ocupando espaço e apagar. |
| **Processos** | Mostra o que roda em primeiro e em segundo plano e permite encerrar o que não precisa. |

### Quarkium Score
| Recurso | Descrição |
|---|---|
| **Teste de score** | Mede CPU, RAM e disco em cerca de 10 segundos e gera uma nota de 0 a 1000. Compare com o teste anterior para ver o efeito das otimizações no **seu** PC. |
| **Diagnóstico de gargalo** | Observa o PC por alguns segundos e indica o que mais limita o desempenho (disco, memória ou CPU), além dos pontos fracos do hardware. |

## Vantagens

- **Feito para o seu hardware.** As recomendações mudam conforme o seu PC: o que vale para SSD não é aplicado em HDD, e o que vale para desktop não é marcado em notebook.
- **Você está no controle.** Nada é aplicado sem você confirmar, e os ajustes de risco médio nunca vêm marcados automaticamente.
- **Reversível.** Os ajustes de registro e de serviços guardam o valor original e podem ser desfeitos pela interface. O programa também oferece criar um ponto de restauração antes de começar.
- **Proteções embutidas.** O Quarkium recusa apagar pastas críticas do sistema (como `Windows`, `Program Files` e `Users`) e não encerra processos essenciais do Windows.
- **Confirmação para ações destrutivas.** Apagar arquivos, encerrar processos e remover apps exige segurar o botão por 3 segundos, para evitar cliques por engano.
- **Um único arquivo.** É só baixar o `.exe` e abrir. Não precisa instalar o .NET nem nenhum outro componente.
- **Roda bem em PC fraco.** Escolha o modo visual **Light** (sem animações, mínimo uso de CPU e GPU) ou **Physics** (transições, partículas e animações) e troque quando quiser.
- **Em 3 idiomas.** Interface em Português (BR), English e Español.
- **Atualizações seguras.** O app confere sozinho se há versão nova e só instala atualizações com assinatura digital válida.
- **Transparente.** O Quarkium só se conecta à internet para login e verificação da licença e para checar atualizações.

## Requisitos

- Windows 10 ou Windows 11 (64 bits)
- Permissão de administrador (necessária para alterar serviços e configurações do sistema)
- Conexão com a internet para login, ativação e verificação da licença
- Uma conta Google ou Discord para entrar e uma License Key válida

## Como começar

1. **Compre** a sua licença em [HTTP_???](HTTP_???) e guarde a License Key que você receber.
2. **Baixe** o `Quarkium.exe` na página de [Releases](https://github.com/Quarkium-Labs/Quarkium/releases/latest).
3. **Abra** o programa como administrador, entre com Google ou Discord e informe a sua License Key.
4. **Escolha o modo visual** e, na tela inicial, veja o hardware detectado.
5. **Crie um ponto de restauração**, revise as otimizações recomendadas e aplique.

> Baixe o Quarkium somente por esta página. Se o Windows SmartScreen ou o antivírus exibir um aviso na primeira execução, é comum em programas que alteram configurações do sistema. Confirme que o arquivo veio deste repositório antes de continuar.

## Licença e ativação

- A License Key fica vinculada à conta que a ativou e ao número de computadores previsto no seu plano.
- A licença é verificada ao abrir o programa e de tempos em tempos enquanto ele estiver em uso.
- Trocou de computador? Fale com o suporte para liberar o aparelho antigo.
- **Não compartilhe a sua chave.** Chaves compartilhadas ou revendidas podem ser revogadas.

## Boas práticas e limites

- Teste primeiro as mudanças e use o ponto de restauração antes de aplicar muitos ajustes de uma vez.
- **Remover apps pré-instalados não é reversível pelo Quarkium.** Se precisar de um app de volta, reinstale pela Microsoft Store. Isso aparece marcado no programa.
- Grandes atualizações do Windows podem desfazer alguns ajustes. Basta aplicar de novo.
- O botão "Liberar RAM" reduz a memória usada pelos processos de forma temporária. O Windows já gerencia a memória bem, e o ganho mais duradouro vem de desativar o que você não precisa que abra.
- Os resultados variam de PC para PC. Use o **Quarkium Score** para medir a diferença no seu equipamento.

## Suporte

Precisa de ajuda com instalação, ativação ou troca de computador?

- **Contato:** quarkium.group@proton.me

Ao pedir suporte, informe a versão do Quarkium, a versão do Windows e, se houver, a mensagem exibida na tela.

## Licença de uso

O Quarkium é um software proprietário, licenciado e não vendido. O uso está sujeito aos termos do arquivo [LICENSE](LICENSE).

© 2026 Quarkium. Todos os direitos reservados. Quarkium e o logotipo Quarkium são marcas do titular.
