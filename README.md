<body>
    <h1>Projeto de Manutenção Preditiva com Machine Learning</h1>
    <p>Este projeto visa aplicar técnicas de Machine Learning para predição de falhas em equipamentos industriais com base em diversas condições ambientais e do equipamento. A seguir, apresento uma visão geral do projeto:</p>
    <h2>Conjunto de Dados</h2>
    <p>O conjunto de dados utilizado contém informações cruciais para a predição de falhas, incluindo:</p>
    <ul>
        <li><strong>UDI (Identificador Único):</strong> Identificador exclusivo para cada ponto de dados.</li>
        <li><strong>ProductID:</strong> Variantes de qualidade do produto.</li>
        <li><strong>Temperatura do ar e do processo [K]:</strong> Parâmetros relevantes para o processo de fabricação.</li>
        <li><strong>Velocidade de rotação e Torque [rpm, Nm]:</strong> Indicadores essenciais do funcionamento da máquina.</li>
        <li><strong>Desgaste da ferramenta [min]:</strong> Associado às variantes de qualidade, adiciona minutos de desgaste da ferramenta.</li>
        <li><strong>Rótulo 'falha da máquina':</strong> Indica se a máquina falhou para diferentes modos de falha.</li>
    </ul>
    <h2>Modos de Falha</h2>
    <p>A falha da máquina consiste em cinco modos independentes:</p>
    <ul>
        <li><strong>Desgaste da Ferramenta (TWF):</strong> Substituição ou falha após um tempo de desgaste aleatório.</li>
        <li><strong>Dissipação de Calor (HDF):</strong> Falha se a diferença entre temperaturas for inferior a 8,6 K e a velocidade de rotação for inferior a 1380 rpm.</li>
        <li><strong>Energia (PWF):</strong> Falha se a potência estiver abaixo de 3.500 W ou acima de 9.000 W.</li>
        <li><strong>Sobretensão (OSF):</strong> Falha se o produto de desgaste da ferramenta e torque exceder 11.000 minNm.</li>
        <li><strong>Falhas Aleatórias (RNF):</strong> 0,1% de chance independente dos parâmetros de processo.</li>
    </ul>
    <h2>Exploração do Conjunto de Dados</h2>
    <p>Verificação das informações e distribuição dos rótulos. Análise exploratória com gráficos de dispersão e histogramas.</p>
    <h2>Pré-processamento de Dados</h2>
    <p>Resample dos casos de falha para equilibrar as classes. Normalização e codificação de features.</p>
    <h2>Modelagem</h2>
    <h3>Modelo Logístico</h3>
    <p>Treinamento e validação cruzada. Matriz de confusão, curva ROC, e métricas de desempenho.</p>
    <h3>Árvore de Decisão</h3>
    <p>Treinamento e validação cruzada. Matriz de confusão, curva ROC, e métricas de desempenho.</p>
    <h3>Floresta Aleatória</h3>
    <p>Treinamento, validação cruzada e otimização de parâmetros. Curva Precision-Recall e importância de features.</p>
    <h2>Conclusão</h2>
    <p>O projeto apresenta uma abordagem abrangente para a predição de falhas em equipamentos industriais. Os modelos foram avaliados e otimizados, com destaque para a eficácia da Floresta Aleatória. A análise de features fornece insights valiosos sobre os principais indicadores de falha.</p>
    <p>Sinta-se à vontade para explorar, contribuir e aprimorar este projeto!</p>

</body>

</html>
