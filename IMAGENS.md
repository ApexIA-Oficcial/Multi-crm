# Documentação de Gestão de Imagens Locais - JEOOTEC CRM

Todas as imagens do sistema foram configuradas para serem carregadas localmente a partir da pasta `/public/` para garantir que o CRM funcione de forma totalmente offline e independente de conexões externas.

Pode substituir qualquer uma das imagens abaixo pelas suas próprias imagens personalizadas de mesmo nome e formato diretamente no diretório correspondente.

## Lista de Ficheiros e Pastas de Imagens

| Ficheiro Local | Descrição | Resolução Sugerida | Formato |
| :--- | :--- | :--- | :--- |
| `/logo.png` | Logótipo principal da JEOOTEC (exibido na barra lateral e login). | `256 x 256 px` | PNG |
| `/banner-home.png` | Banner de fundo decorativo exibido no painel principal do Dashboard. | `1200 x 400 px` | PNG |
| `/posters/renovacao_pos.png` | Cartaz de Campanha padrão de Renovação de Licenças JEOO-POS. | `800 x 600 px` | PNG |
| `/posters/jeoo_med_v2.png` | Cartaz Promocional do Software de Gestão Clínica JEOO-MED v2.0. | `800 x 600 px` | PNG |
| `/posters/cameras_ip.png` | Cartaz Promocional para Sistemas de Videovigilância e Segurança. | `800 x 600 px` | PNG |

---

## Instruções para Substituição Manual:

1. Prepare as suas novas imagens PNG utilizando as resoluções sugeridas acima.
2. Renomeie o seu ficheiro exatamente para o nome correspondente (exemplo: `logo.png` ou `renovacao_pos.png`).
3. Cole o ficheiro na respetiva pasta dentro do diretório `/public/` (as subpastas como `posters` já se encontram criadas para si).
4. Substitua o ficheiro existente quando solicitado pelo sistema operativo.
5. Limpe o cache do seu navegador web para atualizar os novos visuais instantaneamente no CRM!
