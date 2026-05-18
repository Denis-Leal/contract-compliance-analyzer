# Contract Compliance Analyzer

Solução desktop com OCR para análise automatizada de contratos, detecção de palavras-chave e geração de evidências para processos de compliance e auditoria.

---

## Visão Geral

O Contract Compliance Analyzer é uma aplicação desktop desenvolvida para automatizar processos de análise contratual em larga escala.

A solução permite processar múltiplos contratos PDF simultaneamente, localizar palavras-chave ou expressões regex em todas as páginas e gerar relatórios consolidados com evidências em Excel.

O sistema detecta automaticamente:

* PDFs nativos
* PDFs escaneados/imagem com OCR

O objetivo é reduzir esforço operacional em atividades relacionadas a:

* compliance
* jurídico
* auditoria
* procurement
* gestão de terceiros

---

## Principais Funcionalidades

* Processamento simultâneo de múltiplos contratos
* Detecção automática de PDFs nativos e PDFs imagem
* OCR automático com Tesseract
* Busca por palavras-chave e regex
* Identificação da página da evidência
* Extração de trecho contextual
* Geração de relatório consolidado em Excel
* Separação automática dos contratos encontrados
* Geração automática de arquivo ZIP
* Execução local/offline
* Sem dependência de banco de dados
* Sem necessidade de cloud

---

## Exemplos de Aplicação

* Validação de cláusulas LGPD
* Revisão de cláusulas de confidencialidade
* Verificação de SLA
* Identificação de multas contratuais
* Auditoria documental
* Gestão de fornecedores
* Third-party risk
* Compliance contratual

---

## Stack Utilizada

* Python
* Streamlit
* Tesseract OCR
* pdfplumber
* pdf2image
* pandas
* openpyxl
* PyInstaller

---


## OCR Automático

O sistema detecta automaticamente quando um PDF não possui texto extraível e ativa o processamento OCR.

Tecnologias utilizadas no OCR:

* Tesseract OCR
* Poppler
* pdf2image

Idiomas suportados atualmente:

* Português
* Inglês

---

## Distribuição Desktop

A aplicação é distribuída como pacote desktop Windows.

O usuário final NÃO precisa instalar:

* Python
* Tesseract
* Poppler

Todas as dependências já estão embarcadas no pacote da aplicação.

---

## Como Executar

1. Baixe o arquivo ZIP da release
2. Extraia todos os arquivos
3. Execute:

```text id="2l3g3q"
ContractAnalyzer.exe
```

A aplicação irá:

* iniciar localmente
* abrir automaticamente no navegador
* funcionar totalmente offline

---

## Segurança e Privacidade

Todo o processamento ocorre localmente na máquina do usuário.

Nenhum contrato ou documento é enviado para servidores externos.

Isso é especialmente importante para:

* contratos corporativos
* documentos jurídicos
* evidências de auditoria
* informações sensíveis

---

## Limitações Atuais

* OCR pode ser mais lento em PDFs muito grandes
* PDFs escaneados com baixa qualidade podem reduzir a precisão do OCR
* O Windows Defender pode exibir alerta por ausência de assinatura digital do executável

---

## Roadmap

Melhorias planejadas:

* Classificação automática de cláusulas
* Busca semântica
* Análise contratual com IA
* Dashboard gerencial
* Suporte a múltiplos idiomas OCR
* Melhorias exportação Excel
* Destaque visual de evidências em PDF

---

## Changelog

## v1.0.0

Primeira release pública.

Funcionalidades incluídas:

* Extração de texto PDF
* OCR automático
* Busca por palavras-chave
* Busca por regex
* Relatório consolidado em Excel
* Separação automática dos contratos encontrados
* Exportação ZIP
* Distribuição desktop

---

## Licença

Este repositório contém a release pública e a documentação da aplicação desktop.

O código-fonte permanece privado no momento.
