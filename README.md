# Análise de sentimentos com language Studio no Azure IA

## 1. **Criar um recurso de Language no Azure** 
    Primeiro, eu criei um recurso de Language no meu Azure. Para isso, eu abri o portal do Azure em outra aba do navegador e faria login com a conta Microsoft associada à minha assinatura do Azure. Clicaria no botão "＋Criar um recurso" e pesquisaria por "Language service". Selecionaria para criar um plano de serviço de Language. Manteria a seleção padrão e clicaria em "Continuar" para criar meu recurso.

## 2. **Configurar o recurso de Language** 
    Na página "Criar Language", eu configuraria com as seguintes configurações: Assinatura: Minha assinatura do Azure. Grupo de recursos: Selecionaria ou criaria um grupo de recursos com um nome único. Região: East US. Nome: Inseria um nome único. Nível de preço: Free F0 ou S se Free F0 não estiver disponível.

## 3. **Usar o recurso de Language no Azure AI Language Studio** 
    Em outra aba do navegador, abri o Language Studio e faria login. Quando solicitado com "Selecione um recurso do Azure", faria as seguintes configurações: Diretório do Azure: Diretório Padrão, o diretório que estou usando. Assinatura do Azure: Selecionaria a assinatura que estou usando. Tipo de recurso: Language. Nome do recurso: selecionaria o recurso de serviço de Language que acabei de criar. Então selecionaria "Concluído".

## 4. **Explorar a análise de sentimentos no Azure AI Language Studio**
    Na página "Welcome to Language Studio", em "Classify text", encontraria e selecionaria "Analyze sentiment and mine opinions".
    Selecionei o idioma do texto como "English" e adicionei o seguinte texto para análise:
     "Tired hotel with poor service
        The Royal Hotel, London, United Kingdom
        5/6/2018
        This is an old hotel (has been around since 1950's) and the room furnishings are average - becoming a bit old now and require changing. The internet didn't work and had to come to one of their office rooms to check in for my flight home. The website says it's close to the British Museum, but it's too far to walk."
<em>['Text box'](/imagens/LanguageStudioTextBox.png)</em>
<em>['Análise'](/imagens/LanguageStudioAnalise.png)</em>

## 5. **Criar um recurso de Speech no Azure AI Speech Studio**
    Em outra aba do navegador, abri o Azure AI Speech Studio e faria login com minha conta Microsoft. Selecionaria "Configurações" e depois "Criar um recurso". Configuraria com as seguintes configurações: Nome do novo recurso: Inseriria um nome único. Assinatura: Minha assinatura do Azure. Região: Selecionaria uma região suportada. Nível de preço: Free FO (se disponível, caso contrário selecionaria Standard S0). Grupo de recursos: Selecionaria ou criaria um grupo de recursos com um nome único. Selecionaria "Criar recurso". Aguardaria até que o recurso fosse criado e então selecionaria "Usar recurso"⁴.

## 6. **Explorar a transcrição de fala em texto no Speech Studio**
    Na página "Comece com Speech", em "Fala para texto", encontraria "Transcrição de fala em tempo real". Selecionaria "Experimentar Transcrição de fala em tempo real". Em "Escolher arquivos de áudio", selecionaria "Procurar arquivos" e navegaria até a pasta onde salvei o arquivo. Selecionaria "WhatAICanDo.m4a" ou um áudio de sua autoria e depois "Abrir". O serviço de Speech transcreveria e exibiria o texto em tempo real.
<em>['Speech studio'](/imagens/speechStudio.png)</em>

### Documentação:
    Language Studio: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html
    Speech Studio: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html
    
