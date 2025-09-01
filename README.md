<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Liberty American Visa - Assessoria para Visto Americano B1/B2</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .gradient-bg {
            background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 50%, #60a5fa 100%);
        }
        .card-hover {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="gradient-bg text-white shadow-lg">
        <div class="container mx-auto px-6 py-8">
            <div class="text-center">
                <h1 class="text-4xl md:text-5xl font-bold mb-4">Liberty American Visa</h1>
                <p class="text-xl md:text-2xl font-light">Assessoria Especializada em Vistos Americanos B1/B2</p>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-6">
                Realize seu Sonho Americano
            </h2>
            <p class="text-lg text-gray-600 mb-8 max-w-3xl mx-auto">
                Assessoria completa e personalizada para obtenção do seu visto americano B1/B2. 
                Com anos de experiência, oferecemos suporte especializado em cada etapa do processo.
            </p>
            <button onclick="contactWhatsApp()" class="bg-green-600 hover:bg-green-700 text-white font-bold py-4 px-8 rounded-lg text-lg transition duration-300 shadow-lg">
                Falar no WhatsApp Agora
            </button>
        </div>
    </section>

    <!-- Services Section -->
    <section class="py-16 bg-gray-100">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Nossos Serviços</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-lg shadow-md card-hover">
                    <h3 class="text-xl font-bold text-blue-800 mb-4">Visto B1 - Negócios</h3>
                    <p class="text-gray-600 mb-6">
                        Assessoria completa para viagens de negócios, reuniões, conferências e atividades comerciais nos EUA.
                    </p>
                    <button onclick="contactWhatsApp('B1')" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 px-6 rounded-lg transition duration-300">
                        Solicitar Assessoria B1
                    </button>
                </div>
                
                <div class="bg-white p-8 rounded-lg shadow-md card-hover">
                    <h3 class="text-xl font-bold text-blue-800 mb-4">Visto B2 - Turismo</h3>
                    <p class="text-gray-600 mb-6">
                        Orientação especializada para viagens de turismo, visitas familiares e atividades recreativas nos EUA.
                    </p>
                    <button onclick="contactWhatsApp('B2')" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 px-6 rounded-lg transition duration-300">
                        Solicitar Assessoria B2
                    </button>
                </div>
                
                <div class="bg-white p-8 rounded-lg shadow-md card-hover">
                    <h3 class="text-xl font-bold text-blue-800 mb-4">Consultoria Completa</h3>
                    <p class="text-gray-600 mb-6">
                        Análise do perfil, preparação de documentos, treinamento para entrevista e acompanhamento total.
                    </p>
                    <button onclick="contactWhatsApp('Consultoria')" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 px-6 rounded-lg transition duration-300">
                        Consultoria Personalizada
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Process Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Como Funciona</h2>
            <div class="grid md:grid-cols-4 gap-8">
                <div class="text-center">
                    <div class="bg-blue-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <span class="text-2xl font-bold text-blue-800">1</span>
                    </div>
                    <h3 class="text-lg font-semibold text-gray-800 mb-2">Contato Inicial</h3>
                    <p class="text-gray-600">Entre em contato via WhatsApp para uma consulta inicial gratuita</p>
                </div>
                
                <div class="text-center">
                    <div class="bg-blue-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <span class="text-2xl font-bold text-blue-800">2</span>
                    </div>
                    <h3 class="text-lg font-semibold text-gray-800 mb-2">Análise do Perfil</h3>
                    <p class="text-gray-600">Avaliamos seu perfil e definimos a melhor estratégia para seu caso</p>
                </div>
                
                <div class="text-center">
                    <div class="bg-blue-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <span class="text-2xl font-bold text-blue-800">3</span>
                    </div>
                    <h3 class="text-lg font-semibold text-gray-800 mb-2">Preparação</h3>
                    <p class="text-gray-600">Orientamos na documentação e preparamos você para a entrevista</p>
                </div>
                
                <div class="text-center">
                    <div class="bg-blue-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <span class="text-2xl font-bold text-blue-800">4</span>
                    </div>
                    <h3 class="text-lg font-semibold text-gray-800 mb-2">Sucesso</h3>
                    <p class="text-gray-600">Acompanhamos até a aprovação do seu visto americano</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Interview Questions Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Perguntas Frequentes na Entrevista</h2>
            <div class="max-w-4xl mx-auto">
                <p class="text-lg text-gray-600 text-center mb-8">
                    Preparamos você para as principais perguntas que podem ser feitas durante a entrevista no consulado americano
                </p>
                <div class="grid md:grid-cols-2 gap-6">
                    <div class="bg-blue-50 p-6 rounded-lg">
                        <h3 class="text-lg font-semibold text-blue-800 mb-3">Perguntas sobre o Propósito da Viagem</h3>
                        <ul class="text-gray-700 space-y-2">
                            <li>• Qual o motivo da sua viagem aos Estados Unidos?</li>
                            <li>• Por quanto tempo pretende ficar?</li>
                            <li>• Onde vai se hospedar?</li>
                            <li>• Já visitou os EUA antes?</li>
                            <li>• Tem parentes ou amigos nos Estados Unidos?</li>
                        </ul>
                    </div>
                    
                    <div class="bg-green-50 p-6 rounded-lg">
                        <h3 class="text-lg font-semibold text-green-800 mb-3">Perguntas sobre Situação Financeira</h3>
                        <ul class="text-gray-700 space-y-2">
                            <li>• Qual sua profissão?</li>
                            <li>• Quem vai pagar pela viagem?</li>
                            <li>• Qual sua renda mensal?</li>
                            <li>• Tem bens no Brasil?</li>
                            <li>• Como vai comprovar que tem recursos?</li>
                        </ul>
                    </div>
                    
                    <div class="bg-purple-50 p-6 rounded-lg">
                        <h3 class="text-lg font-semibold text-purple-800 mb-3">Perguntas sobre Vínculos no Brasil</h3>
                        <ul class="text-gray-700 space-y-2">
                            <li>• É casado(a)? Tem filhos?</li>
                            <li>• Trabalha há quanto tempo na empresa atual?</li>
                            <li>• Tem casa própria no Brasil?</li>
                            <li>• Estuda? Em que instituição?</li>
                            <li>• O que te faz querer voltar ao Brasil?</li>
                        </ul>
                    </div>
                    
                    <div class="bg-orange-50 p-6 rounded-lg">
                        <h3 class="text-lg font-semibold text-orange-800 mb-3">Perguntas Gerais</h3>
                        <ul class="text-gray-700 space-y-2">
                            <li>• Fala inglês?</li>
                            <li>• Já teve visto negado antes?</li>
                            <li>• Conhece alguém que mora nos EUA?</li>
                            <li>• Tem outros vistos internacionais?</li>
                            <li>• Pretende trabalhar nos Estados Unidos?</li>
                        </ul>
                    </div>
                </div>
                <div class="text-center mt-8">
                    <button onclick="contactWhatsApp('Preparação para Entrevista')" class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-8 rounded-lg transition duration-300">
                        Quero Preparação para Entrevista
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section class="py-16 bg-gray-100">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Investimento na Sua Aprovação</h2>
            <div class="max-w-4xl mx-auto">
                <div class="bg-white rounded-lg shadow-xl overflow-hidden">
                    <div class="bg-blue-600 text-white text-center py-6">
                        <h3 class="text-2xl font-bold">Assessoria Completa + DS-160</h3>
                        <p class="text-blue-100 mt-2">Tudo que você precisa para conseguir seu visto</p>
                    </div>
                    
                    <div class="p-8">
                        <div class="text-center mb-8">
                            <span class="text-5xl font-bold text-gray-800">R$ 980</span>
                            <span class="text-gray-600 text-xl">,00</span>
                        </div>
                        
                        <div class="grid md:grid-cols-2 gap-8 mb-8">
                            <div>
                                <h4 class="text-xl font-semibold text-gray-800 mb-4">O que está incluído:</h4>
                                <ul class="space-y-3 text-gray-700">
                                    <li class="flex items-start">
                                        <span class="text-green-600 font-bold mr-2">✓</span>
                                        Análise completa do seu perfil
                                    </li>
                                    <li class="flex items-start">
                                        <span class="text-green-600 font-bold mr-2">✓</span>
                                        Preenchimento do formulário DS-160
                                    </li>
                                    <li class="flex items-start">
                                        <span class="text-green-600 font-bold mr-2">✓</span>
                                        Orientação sobre documentação
                                    </li>
                                    <li class="flex items-start">
                                        <span class="text-green-600 font-bold mr-2">✓</span>
                                        Preparação para entrevista
                                    </li>
                                    <li class="flex items-start">
                                        <span class="text-green-600 font-bold mr-2">✓</span>
                                        Suporte até a aprovação
                                    </li>
                                </ul>
                            </div>
                            
                            <div class="bg-blue-50 p-6 rounded-lg">
                                <h4 class="text-lg font-semibold text-blue-800 mb-3">Sobre o Formulário DS-160</h4>
                                <p class="text-gray-700 text-sm mb-3">
                                    O DS-160 é o formulário oficial obrigatório para solicitação de visto americano. É um documento complexo com mais de 20 páginas que deve ser preenchido com precisão absoluta.
                                </p>
                                <p class="text-gray-700 text-sm mb-3">
                                    Qualquer erro pode resultar na negação do visto. Por isso, nosso preenchimento profissional garante que todas as informações estejam corretas e otimizadas para aprovação.
                                </p>
                                <p class="text-blue-800 font-semibold text-sm">
                                    Economize tempo e evite erros custosos!
                                </p>
                            </div>
                        </div>
                        
                        <div class="text-center">
                            <button onclick="contactWhatsApp('Pagamento - Assessoria Completa R$ 980')" class="bg-green-600 hover:bg-green-700 text-white font-bold py-4 px-8 rounded-lg text-lg transition duration-300 mb-4">
                                Contratar Assessoria - R$ 980,00
                            </button>
                            <p class="text-gray-600 text-sm">
                                Entre em contato para informações sobre formas de pagamento
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Choose Us Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Por que Escolher a Liberty American Visa</h2>
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="bg-green-100 w-8 h-8 rounded-full flex items-center justify-center mr-4 mt-1">
                                <span class="text-green-600 font-bold">✓</span>
                            </div>
                            <div>
                                <h3 class="text-lg font-semibold text-gray-800">Experiência Comprovada</h3>
                                <p class="text-gray-600">Anos de experiência em assessoria para vistos americanos</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-green-100 w-8 h-8 rounded-full flex items-center justify-center mr-4 mt-1">
                                <span class="text-green-600 font-bold">✓</span>
                            </div>
                            <div>
                                <h3 class="text-lg font-semibold text-gray-800">Atendimento Personalizado</h3>
                                <p class="text-gray-600">Cada caso é único e recebe atenção especializada</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-green-100 w-8 h-8 rounded-full flex items-center justify-center mr-4 mt-1">
                                <span class="text-green-600 font-bold">✓</span>
                            </div>
                            <div>
                                <h3 class="text-lg font-semibold text-gray-800">Suporte Completo</h3>
                                <p class="text-gray-600">Acompanhamento em todas as etapas do processo</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-green-100 w-8 h-8 rounded-full flex items-center justify-center mr-4 mt-1">
                                <span class="text-green-600 font-bold">✓</span>
                            </div>
                            <div>
                                <h3 class="text-lg font-semibold text-gray-800">Comunicação Direta</h3>
                                <p class="text-gray-600">Contato direto via WhatsApp para maior agilidade</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="bg-white p-8 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6 text-center">Pronto para Começar?</h3>
                    <p class="text-gray-600 mb-6 text-center">
                        Entre em contato agora mesmo e dê o primeiro passo para realizar seu sonho americano.
                    </p>
                    <button onclick="contactWhatsApp()" class="w-full bg-green-600 hover:bg-green-700 text-white font-bold py-4 px-6 rounded-lg text-lg transition duration-300">
                        Falar no WhatsApp
                    </button>
                    <p class="text-sm text-gray-500 text-center mt-4">
                        Resposta rápida garantida
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="py-16 bg-blue-900 text-white">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold mb-6">Entre em Contato</h2>
            <p class="text-xl mb-8">
                Tire suas dúvidas e solicite sua assessoria personalizada
            </p>
            <div class="max-w-md mx-auto">
                <button onclick="contactWhatsApp()" class="w-full bg-green-600 hover:bg-green-700 text-white font-bold py-4 px-6 rounded-lg text-lg transition duration-300 mb-4">
                    WhatsApp: (61) 98152-5815
                </button>
                <p class="text-blue-200">
                    Clique no botão acima para falar diretamente conosco
                </p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-6 text-center">
            <h3 class="text-2xl font-bold mb-4">Liberty American Visa</h3>
            <p class="text-gray-400 mb-4">
                Assessoria Especializada em Vistos Americanos B1/B2
            </p>
            <p class="text-gray-500 text-sm">
                Todos os direitos reservados. Assessoria profissional para obtenção de vistos americanos.
            </p>
        </div>
    </footer>

    <script>
        function contactWhatsApp(service = '') {
            const phone = '5561981525815';
            let message = 'Olá! Gostaria de saber mais sobre a assessoria para visto americano da Liberty American Visa.';
            
            if (service) {
                message += ` Tenho interesse especificamente no serviço: ${service}.`;
            }
            
            const whatsappUrl = `https://wa.me/${phone}?text=${encodeURIComponent(message)}`;
            window.open(whatsappUrl, '_blank');
        }

        // Smooth scrolling for better user experience
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'97815edf4671622e',t:'MTc1NjY5NDA4Ny4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
