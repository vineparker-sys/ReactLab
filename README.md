- # **Instruções para Instalação e Uso do Software ReactLab**

---
- ## 1. **Introdução** 
  O software **ReactLab** foi desenvolvido para automatizar a análise de reatividade ASTM, facilitando o registro de temperaturas de termopares durante medições de tempo pré-definidas. Este guia explica passo a passo como utilizar o software e realizar as medições de forma simples e eficiente.  
  
---
- ## 2. **Requisitos do Sistema**
- **Sistema Operacional**: Windows 10 ou superior
- **Driver para Cabo Conversor USB para Serial DB9 (RS232)**:
	- **Driver**: TrendNet TU-S9
	- **Link para download do driver**: [Driver TU-S9](https://downloads.trendnet.com/tu-s9_v3_2/driver/drivers_tu-s9v3_windows.zip) - https://downloads.trendnet.com/tu-s9_v3_2/driver/drivers_tu-s9v3_windows.zip
- **Acesso à internet** (para baixar o driver caso ainda não esteja instalado).
  
---
- ## 3. **Instalação e Configuração Inicial**
- ### 3.1 **Baixar o software**:
	- O software **ReactLab** está empacotado como um único executável e pode ser encontrado na pasta `C:/ReactLab`.
- ### 3.2 **Instalar o driver do cabo USB para Serial**:
	- **Conecte o conversor USB para Serial** ao computador.
	- Instale o **driver do conversor serial para USB -  TU-S9**.
- ### 3.3 **Configurar o Termômetro**:
	- Conecte o termômetro Lutron TM-947SD via cabo RS232 para USB.
- ### 3.4 **Configuração da Porta COM**:
	- 1. Após instalar o driver e conectar o conversor USB-Serial, **abra o Gerenciador de Dispositivos** no seu computador:
	- Pressione as teclas `Windows + X` e selecione **Gerenciador de Dispositivos**.
	- 2. Na lista de dispositivos, encontre a seção **Portas (COM & LPT)** e expanda-a.
	- 3. Você verá algo como **"USB to Serial Adapter (COMx)"**, onde `COMx` será o número atribuído automaticamente à porta.
	- 4. Para alterar a porta para `COM12`, clique com o botão direito no dispositivo e selecione **Propriedades**.
	- 5. Na aba **Configurações da Porta**, clique em **Avançado...**.
	- 6. No campo **Número da Porta COM**, escolha **COM12**.
	- 7. Clique em **OK** e reinicie o computador.
	    
---
- ## 4. **Iniciando o Programa** 

 1. **Navegue até a pasta onde o software está instalado** (`C:/ReactLab`).
	
 2. **Clique duas vezes no arquivo executável** (`ReactLab.exe`).
	
 3. O software será iniciado e exibirá o cabeçalho e o menu principal, solicitando a seleção da duração da análise.

---
- ## 5. **Utilizando o Programa**

- ### 5.1 **Escolhendo a Duração da Análise** 
  O software oferece diferentes opções de duração para a análise de temperatura. Quando o menu aparecer, você verá as seguintes opções:  
- ![image](https://github.com/user-attachments/assets/af503f5b-6af4-4c5d-b257-435419a64d5d)

- **Digite o número da opção** correspondente ao tempo desejado e pressione `Enter`. Por exemplo, para escolher uma medição de 5 minutos, digite `4`.

- ### 5.2 **Inserindo os Códigos das Amostras**
  Após escolher a duração da análise, o software vai identificar os termopares ativos. Ele exibirá uma mensagem solicitando que você insira o código da amostra para cada termopar ativo.  
  
  Exemplo:  
- 	![image](https://github.com/user-attachments/assets/fba4b58d-dd9d-4c56-92b2-af204ee2c8b2)

- **Digite o código** de cada amostra e pressione `Enter` para cada termopar.

- ### 5.3 **Preparação para a Medição** 
  Antes de iniciar a medição, o software mostrará a seguinte mensagem:  
  
- 	![image](https://github.com/user-attachments/assets/4f0cc121-94c8-4cae-a631-0212a9a896dd)

  
- **Insira a amostra** no recipiente e pressione `Enter` para iniciar a medição. A partir desse momento, o software começará a registrar as temperaturas a cada intervalo de tempo.

- ### 5.4 **Exportando os Resultados** 
  Ao término da medição, o software perguntará se você deseja exportar os dados:  

- ![image](https://github.com/user-attachments/assets/06bc214e-f716-4b48-9968-add3bb95fa5f)


- **Digite 's'** para exportar os dados. O arquivo de resultados será salvo automaticamente na área de trabalho:

- ![image](https://github.com/user-attachments/assets/09fba2a0-a45d-4883-bed1-d6c6cc17052d)


- Em seguida, o software perguntará se deseja realizar outra medição.
  
---
- ## 6. **Soluções de Problemas Comuns**

- ### 6.1 **Erro ao abrir a porta serial**
- **Problema**: O erro `"Erro ao abrir a porta serial. Verifique a conexão"` aparece quando o software não consegue se conectar ao termômetro.
- **Solução**: Verifique se o termômetro está conectado corretamente na porta USB do computador. Certifique-se de que a porta COM configurada no software é a mesma em que o dispositivo está conectado (por padrão, `COM12`).

- ### 6.2 **A tela fica bloqueada após 15 minutos de inatividade**
- **Problema**: A tela do computador é bloqueada automaticamente, interrompendo a medição.
- **Solução**: O software tem um recurso que impede o bloqueio da tela movendo o cursor automaticamente a cada 60 segundos. Se isso não funcionar, verifique as configurações de energia do sistema.

- ### 6.3 **Arquivo de exportação não aparece na área de trabalho**
- **Problema**: A exportação de dados foi concluída, mas o arquivo não está visível na área de trabalho.
- **Solução**: Verifique se a exportação foi concluída corretamente, e se o arquivo foi salvo na pasta correta. A mensagem no console deve confirmar que o arquivo foi salvo na "Área de Trabalho".

- ### 6.4 **O software não inicia**
- **Problema**: Ao tentar executar o software, ele não responde ou mostra uma mensagem de erro.
- **Solução**: Verifique se o driver do conversor USB para Serial foi instalado corretamente e se está com o sistema operacional atualizado.
  
---
- ## **Conclusão**
  Este guia deve ajudar a utilizar o software ReactLab de forma simples e eficiente. Siga as instruções e esteja atento às mensagens do console para garantir que as medições sejam realizadas com sucesso. Caso encontre algum erro não documentado, entre em contato com o suporte técnico.  
  
---
- ## **Informações Adicionais**
  Caso tenha dúvidas sobre a instalação do driver ou o uso do software, consulte a equipe de suporte de TI da Lhoist.
