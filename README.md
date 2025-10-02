# 🚀 Implantação de Automatização com CloudFormation

---
## 📌 Visão Geral
- O CloudFormation é um **serviço que facilita a modelagem e configurações de recursos na AWS**.  
- Com o CloudFormation é eliminada a necessidade de configurar recursos manualmente.
- O foco passa a ser para o desenvolvimento e  gestão dos aplicativos.  
- Com ele é possível criar modelos de pilhas de infraestrutura, permitindo a replicação.  
- Auxilia a garantir que todos os recursos sejam configurados conforme as regras, politicas e boas práticas de segurança.

![a1](https://github.com/user-attachments/assets/b64328b2-1d14-4755-8f45-d7d4ec9a9648)

---

## 📂 CloudFormation suporta JSON e YAML.
- JSON  
  ![json](https://github.com/user-attachments/assets/d3411cda-fb2e-4626-b1d5-aab4a71a5114)

- YAML  
  ![yaml](https://github.com/user-attachments/assets/05248543-a8a4-49b3-88dc-5852cd13a485)

---

## ⚙️ Passos para AUTOMATIZAÇÃO:
- Na console AWS, no serviço de AWS CloudFormation, selecione o botão criar STACK (PILHA)  
  ![etapa 1](https://github.com/user-attachments/assets/27b38f12-e31e-4e32-bfc6-1931dc905d3e)

- Na página seguinte selecione a opção **Gerador IaC**  
  ![etapa 2](https://github.com/user-attachments/assets/0643c0cb-1519-4c10-a225-6079404434a8)

- O console será direcionado para uma nova página, em que terá as opções para criar um novo modelo ou visualçizar modelos existentes.  
  ![etapa 3](https://github.com/user-attachments/assets/19af7fdb-b2f2-4b91-a3da-f3f9edffa448)

- Selecionando criar novo modelo, o console abre na primeira etapa para detalhar as especificações do modelo
  - Nome do modelo
  - Politica de exclusão -> comportamento do recurso caso a pilha seja excluída
  - E politica de substituição -> comportamento do recurso na situação da pilha ser atualizada  

  ![etapa 4](https://github.com/user-attachments/assets/befebdab-3b96-4a97-a444-7888edc3d79d)

- Na etapa seguinte é adicionado os recursos provisionados que serão verificados  
  ![etapa 5](https://github.com/user-attachments/assets/2c98c240-9651-4f48-afbe-d00ac5775216)

- Emseguida seleciona os recursos recomendados para o modelo  
  ![etapa 6](https://github.com/user-attachments/assets/4b7fcf05-08de-4da8-9b4a-532f027c08c9)

- Por fim, revisa e cria o modelo  
  ![etapa 7](https://github.com/user-attachments/assets/a0d4cdfe-0de0-4417-b3f4-8cc392b985be)

---

## 🔎 Após a criação, é possível visualizar o modelo na página do Gerador IaC, clicando em visualizar modelos
![visualizar](https://github.com/user-attachments/assets/6822b728-0405-4f47-87af-edd69595c024)

---

## 🎨 Outro método mais visual para criar pilhas é utilizando o Composer
![composer](https://github.com/user-attachments/assets/6cf119e1-4c70-40c8-85db-b98bb90a4ea6)
