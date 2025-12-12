# Offer
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Qingbei University - Admission Acceptance Portal</title>
    <style>
        /* 基础样式 - 兼容邮件和网页 */
        body {
            margin: 0;
            padding: 20px;
            background-color: #f8f9fa;
            color: #333;
            font-family: 'Times New Roman', Georgia, serif;
            line-height: 1.6;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: #ffffff;
            border-top: 8px solid #0d47a1;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .letterhead {
            padding: 40px 40px 20px 40px;
            border-bottom: 1px solid #e0e0e0;
        }
        
        .university-name {
            font-size: 28px;
            font-weight: bold;
            color: #0d47a1;
            margin-bottom: 5px;
        }
        
        .school-name {
            font-size: 18px;
            color: #555;
            margin-bottom: 10px;
        }
        
        .address {
            font-size: 14px;
            color: #777;
            margin-top: 20px;
            line-height: 1.4;
        }
        
        .date {
            font-size: 16px;
            color: #555;
            margin-top: 30px;
            text-align: right;
        }
        
        .content {
            padding: 30px 40px;
        }
        
        .salutation {
            font-size: 18px;
            margin-bottom: 25px;
            color: #333;
        }
        
        .congrats {
            font-size: 24px;
            color: #0d47a1;
            margin-bottom: 25px;
            font-weight: bold;
            text-align: center;
        }
        
        .message {
            font-size: 16px;
            margin-bottom: 20px;
            line-height: 1.7;
        }
        
        .highlight {
            background-color: #f5f9ff;
            padding: 20px;
            margin: 25px 0;
            border-left: 4px solid #0d47a1;
            font-style: italic;
        }
        
        .funding-section {
            background-color: #f8f9fa;
            padding: 25px;
            margin: 30px 0;
            border: 1px solid #e0e0e0;
        }
        
        .funding-title {
            font-size: 20px;
            color: #0d47a1;
            margin-bottom: 15px;
            font-weight: bold;
        }
        
        .funding-item {
            margin: 12px 0;
            padding-left: 20px;
            position: relative;
            font-size: 15px;
        }
        
        .funding-item:before {
            content: "•";
            position: absolute;
            left: 5px;
            color: #0d47a1;
            font-size: 20px;
        }
        
        .conditions {
            background-color: #f8f9fa;
            padding: 20px;
            margin: 25px 0;
            border-left: 4px solid #1565c0;
        }
        
        /* 按钮样式 */
        .accept-button {
            display: block;
            width: 300px;
            margin: 40px auto;
            padding: 15px;
            background-color: #0d47a1;
            color: white;
            border: none;
            border-radius: 4px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            text-align: center;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: background-color 0.3s;
        }
        
        .accept-button:hover {
            background-color: #1565c0;
        }
        
        .accept-button.accepted {
            background-color: #4CAF50;
            cursor: default;
        }
        
        .footer {
            text-align: center;
            padding: 25px;
            color: #666;
            font-size: 14px;
            border-top: 1px solid #e0e0e0;
            background-color: #f8f9fa;
        }
        
        .signature {
            margin-top: 60px;
            padding-right: 20px;
            color: #333;
            font-size: 16px;
        }
        
        .signature-name {
            font-weight: bold;
            font-size: 18px;
            margin-top: 40px;
            color: #0d47a1;
        }
        
        .signature-title {
            font-size: 15px;
            color: #555;
            margin-top: 5px;
        }
        
        .portal-hint {
            text-align: center;
            margin-top: 30px;
            font-size: 14px;
            color: #777;
            font-style: italic;
        }
        
        .seal {
            float: right;
            width: 80px;
            height: 80px;
            border-radius: 50%;
            border: 2px solid #0d47a1;
            text-align: center;
            line-height: 1.2;
            padding: 10px;
            font-size: 12px;
            font-weight: bold;
            color: #0d47a1;
            background-color: white;
            margin-left: 20px;
        }
        
        /* 确认消息 */
        .confirmation-message {
            display: none;
            text-align: center;
            padding: 30px;
            background-color: #f5f9ff;
            border-radius: 8px;
            margin-top: 30px;
            border: 2px solid #4CAF50;
        }
        
        .confirmation-message h3 {
            color: #4CAF50;
            margin-bottom: 15px;
        }
        
        .confirmation-icon {
            font-size: 48px;
            margin-bottom: 20px;
            color: #4CAF50;
        }
        
        /* 响应式设计 */
        @media (max-width: 600px) {
            .letterhead, .content {
                padding: 20px;
            }
            
            .university-name {
                font-size: 24px;
            }
            
            .accept-button {
                width: 90%;
                font-size: 16px;
            }
            
            .seal {
                float: none;
                margin: 20px auto;
                display: block;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="letterhead">
            <div class="seal">
                QINGBEI<br>UNIVERSITY
            </div>
            
            <div class="university-name">QINGBEI UNIVERSITY</div>
            <div class="school-name">School of Unconditional Love</div>
            
            <div class="address">
                Offer Avenue<br>
                Xinfan Town, Chengdu City<br>
                People's Republic of China<br>
                Tel: 18080817059
            </div>
            
            <div class="date" id="currentDate">December 25, 2024</div>
            
            <div style="clear: both;"></div>
        </div>
        
        <div class="content">
            <div class="salutation">Dear <span id="recipientName">Charlotte</span>,</div>
            
            <div class="congrats">OFFER OF ADMISSION</div>
            
            <div class="message">
                On behalf of Qingbei University, I am pleased to offer you admission to the <span style="font-weight: bold; color: #0d47a1;">PhD Program in "Chi Xiang's Favorite Person"</span> at the <strong>School of Unconditional Love</strong> for the Fall 2026 semester.
            </div>
            
            <div style="font-style: italic; margin: 20px 0; color: #555; font-size: 16px;">
                This decision was made after a comprehensive review of your application by the Office of Graduate Admissions.
            </div>
            
            <div class="highlight">
                The Admissions Committee, under the direction of <strong>Roy</strong>, was particularly impressed by your unique perspicacity, exceptional capabilities, and the dedication demonstrated in your application materials. Your refined WeChat moments further exemplified your attention to detail and personal brand cultivation.
            </div>
            
            <div class="funding-section">
                <div class="funding-title">Funding Package</div>
                
                <div class="funding-item">
                    <strong>Full Tuition Waiver:</strong> You will unconditionally and exclusively enjoy every bit of Chi Xiang's love.
                </div>
                
                <div class="funding-item">
                    <strong>Living Stipend:</strong> Unlimited hugs and kisses, dispensed upon request.
                </div>
                
                <div class="funding-item">
                    <strong>Research Grant:</strong> Fully funded wishes of your choice, with no usage limits.
                </div>
                
                <div class="funding-item">
                    <strong>Christmas Bonus:</strong> With this admission letter, you can claim a Christmas gift from Chi Xiang during the holiday season.
                </div>
            </div>
            
            <div class="message">
                This offer of admission is valid until <strong>April 1, 5200</strong>. A non-refundable enrollment deposit of one (1) hug must be submitted to complete your enrollment.
            </div>
            
            <div class="conditions">
                <strong>Conditions of Acceptance:</strong> By reading this letter, you agree to believe in yourself as much as the Committee believes in you. You are brilliant, you are capable, and you are totally going to nail this process.
            </div>
            
            <div class="portal-hint">
                You may access your admission portal at: https://admissions.qingbei.edu/portal<br>
                Your applicant ID is: QB2026-8473
            </div>
            
            <!-- 接受按钮 -->
            <button id="acceptBtn" class="accept-button" onclick="acceptOffer()">ACCEPT ADMISSION OFFER</button>
            
            <!-- 确认消息 -->
            <div id="confirmationMessage" class="confirmation-message">
                <div class="confirmation-icon">✓</div>
                <h3>Admission Accepted Successfully!</h3>
                <p>Congratulations! Your admission to Qingbei University has been confirmed.</p>
                <p>You will receive a confirmation email shortly with next steps.</p>
                <p><strong>Welcome to the Qingbei University family!</strong></p>
                <p style="margin-top: 20px; font-size: 14px; color: #666;">
                    A confirmation number has been generated for your records:<br>
                    <strong style="font-size: 16px;">QB-CONFIRM-2026-8473</strong>
                </p>
            </div>
            
            <div style="clear: both;"></div>
            
            <div class="signature">
                <div>Sincerely,</div>
                <div class="signature-name">Roy</div>
                <div class="signature-title">Director of Graduate Admissions</div>
                <div class="signature-title">School of Unconditional Love</div>
                <div class="signature-title">Qingbei University</div>
            </div>
        </div>
        
        <div class="footer">
            <p>Qingbei University | School of Unconditional Love</p>
            <p style="margin-top: 10px; font-size: 13px;">Offer Avenue, Xinfan Town, Chengdu City | Tel: 18080817059</p>
            <p style="margin-top: 15px; font-size: 12px; color: #999;">This document constitutes an official offer of admission. Please retain for your records.</p>
        </div>
    </div>

    <script>
        // 设置当前日期
        function setCurrentDate() {
            const today = new Date();
            const options = { year: 'numeric', month: 'long', day: 'numeric' };
            document.getElementById('currentDate').textContent = today.toLocaleDateString('en-US', options);
        }
        
        // 从URL参数获取收件人姓名
        function getRecipientName() {
            const urlParams = new URLSearchParams(window.location.search);
            const nameFromUrl = urlParams.get('name');
            if (nameFromUrl) {
                document.getElementById('recipientName').textContent = decodeURIComponent(nameFromUrl);
            }
        }
        
        // 接受录取通知
        function acceptOffer() {
            const button = document.getElementById('acceptBtn');
            const confirmation = document.getElementById('confirmationMessage');
            
            // 更新按钮状态
            button.textContent = 'ADMISSION ACCEPTED ✓';
            button.classList.add('accepted');
            button.disabled = true;
            
            // 显示确认消息
            confirmation.style.display = 'block';
            
            // 滚动到确认消息
            confirmation.scrollIntoView({ behavior: 'smooth', block: 'center' });
            
            // 发送确认到服务器（这里只是模拟）
            sendConfirmationToServer();
            
            // 添加一些视觉反馈
            showCelebration();
        }
        
        // 模拟发送确认到服务器
        function sendConfirmationToServer() {
            // 在实际应用中，这里会发送AJAX请求到服务器
            console.log('Admission acceptance sent to server');
            
            // 模拟API调用
            setTimeout(() => {
                console.log('Server response: Admission confirmed successfully');
            }, 1000);
        }
        
        // 显示庆祝效果
        function showCelebration() {
            // 简单的庆祝效果
            const container = document.querySelector('.container');
            
            // 添加短暂的闪光效果
            container.style.boxShadow = '0 0 30px rgba(76, 175, 80, 0.5)';
            setTimeout(() => {
                container.style.boxShadow = '0 2px 10px rgba(0,0,0,0.1)';
            }, 1000);
            
            // 添加庆祝消息到控制台
            console.log('%c 🎉 Congratulations! Admission Accepted! 🎉', 'color: #4CAF50; font-size: 16px; font-weight: bold;');
        }
        
        // 页面加载时初始化
        window.onload = function() {
            setCurrentDate();
            getRecipientName();
            
            // 检查是否已经接受过（从本地存储）
            if (localStorage.getItem('qingbeiAdmissionAccepted')) {
                document.getElementById('acceptBtn').click();
            }
            
            // 添加页面加载动画
            document.querySelector('.container').style.opacity = '0';
            document.querySelector('.container').style.transform = 'translateY(20px)';
            
            setTimeout(() => {
                document.querySelector('.container').style.transition = 'opacity 0.5s ease, transform 0.5s ease';
                document.querySelector('.container').style.opacity = '1';
                document.querySelector('.container').style.transform = 'translateY(0)';
            }, 100);
        };
        
        // 保存接受状态到本地存储
        function saveAcceptance() {
            localStorage.setItem('qingbeiAdmissionAccepted', 'true');
        }
        
        // 修改acceptOffer函数以保存状态
        const originalAcceptOffer = acceptOffer;
        acceptOffer = function() {
            originalAcceptOffer();
            saveAcceptance();
        };
    </script>
</body>
</html>
