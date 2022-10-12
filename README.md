# Ignite LAb | React | Design System

## Roadmap to start
    - npm create vite@latest
    - cd project-folder
    - npm install

    - npm install -D tailwindcss postcss autoprefixer
    - npx tailwindcss init -p

    - Configura no arquivo tailwind.config.cjs, onde é para ser usado os estilos do tailwind
        - content: ['./src/**/*.tsx']
    - Cria um arquivo de estilo global e adiciona as importações do tailwindcss
        - @tailwind base;
        - @tailwind utilities;
        - @tailwind components;

    - Setup Storybook
        - npx sb init --builder @storybook/builder-vite --use-npm

        - importar o arquivo de estilos global dentro do "./.storybook/preview.cjs" para que as estilizações do tailwindcss funcionem na previsualização do storybook

        - npm run storybook

        - criar o arquivo "./.storybook/manager.js" (opcional)
            - adicionar o tema "dark"

    - Configurar os "tokens" do Figma, dentro do tailwindcss

    - Instalar a biblioteca clsx, é um utilitario para construção de classes condicionais
        - npm install --save clsx

    - Instalar o Radix UI - Slot (flexibiliza ao dev escolher qual tag gostaria de usar no componente)
        - npm install @radix-ui/react-slot
    - Instalar o Radix UI - Checkbox
        - npm install @radix-ui/react-checkbox