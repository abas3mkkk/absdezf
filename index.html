<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>رسائل مجهولة 💌</title>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary: #667eea;
            --secondary: #764ba2;
            --accent: #f093fb;
            --bg: #0f0f1e;
            --surface: #1a1a2e;
            --text: #ffffff;
            --text-secondary: #a0a0a0;
            --success: #4ade80;
            --danger: #f87171;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', sans-serif;
            background: linear-gradient(135deg, var(--bg) 0%, #16213e 100%);
            color: var(--text);
            min-height: 100vh;
            overflow-x: hidden;
            padding-bottom: 70px;
        }

        /* ===== Header ===== */
        .header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 20px rgba(102, 126, 234, 0.3);
            position: sticky;
            top: 0;
            z-index: 100;
            backdrop-filter: blur(10px);
        }

        .header h1 {
            font-size: 24px;
            font-weight: 700;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        /* ===== Navigation ===== */
        .nav-tabs {
            display: flex;
            justify-content: space-around;
            background: var(--surface);
            padding: 10px;
            position: fixed;
            bottom: 0;
            left: 0;
            right: 0;
            z-index: 1000;
            box-shadow: 0 -2px 20px rgba(0, 0, 0, 0.5);
        }

        .nav-tab {
            flex: 1;
            text-align: center;
            padding: 12px;
            cursor: pointer;
            transition: all 0.3s;
            border-radius: 12px;
            color: var(--text-secondary);
        }

        .nav-tab.active {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: var(--text);
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
        }

        .nav-tab i {
            font-size: 24px;
            display: block;
            margin-bottom: 5px;
        }

        .nav-tab span {
            font-size: 12px;
            display: block;
        }

        /* ===== Content ===== */
        .content {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
        }

        .page {
            display: none;
            animation: fadeIn 0.3s;
        }

        .page.active {
            display: block;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* ===== Cards ===== */
        .post-card {
            background: var(--surface);
            border-radius: 16px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            transition: all 0.3s;
            border: 1px solid rgba(102, 126, 234, 0.2);
        }

        .post-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(102, 126, 234, 0.4);
        }

        .post-header {
            display: flex;
            align-items: center;
            gap: 12px;
            margin-bottom: 15px;
        }

        .avatar {
            width: 45px;
            height: 45px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--primary), var(--accent));
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 20px;
            font-weight: bold;
            color: white;
            box-shadow: 0 3px 10px rgba(102, 126, 234, 0.5);
        }

        .post-info h3 {
            font-size: 16px;
            margin-bottom: 3px;
        }

        .post-time {
            font-size: 12px;
            color: var(--text-secondary);
        }

        .post-content {
            margin: 15px 0;
            font-size: 15px;
            line-height: 1.6;
            color: var(--text);
        }

        .post-actions {
            display: flex;
            gap: 15px;
            padding-top: 15px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }

        .action-btn {
            display: flex;
            align-items: center;
            gap: 8px;
            padding: 8px 16px;
            border-radius: 20px;
            background: rgba(102, 126, 234, 0.1);
            border: none;
            color: var(--text);
            cursor: pointer;
            transition: all 0.3s;
            font-size: 14px;
        }

        .action-btn:hover {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            transform: scale(1.05);
        }

        .action-btn.active {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
        }

        /* ===== Input ===== */
        .input-group {
            display: flex;
            gap: 10px;
            margin-bottom: 20px;
        }

        .input-field {
            flex: 1;
            padding: 15px;
            border-radius: 12px;
            background: var(--surface);
            border: 1px solid rgba(102, 126, 234, 0.3);
            color: var(--text);
            font-size: 15px;
            transition: all 0.3s;
        }

        .input-field:focus {
            outline: none;
            border-color: var(--primary);
            box-shadow: 0 0 15px rgba(102, 126, 234, 0.3);
        }

        .btn-primary {
            padding: 15px 30px;
            border-radius: 12px;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            border: none;
            color: white;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            box-shadow: 0 4px 15px rgba(102, 126, 234, 0.4);
        }

        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(102, 126, 234, 0.6);
        }

        /* ===== Theme Selector ===== */
        .theme-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
            margin-top: 20px;
        }

        .theme-card {
            padding: 20px;
            border-radius: 12px;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s;
            border: 2px solid transparent;
        }

        .theme-card:hover {
            transform: scale(1.05);
        }

        .theme-card.active {
            border-color: var(--primary);
            box-shadow: 0 0 20px rgba(102, 126, 234, 0.5);
        }

        .theme-default {
            background: linear-gradient(135deg, #667eea, #764ba2);
        }

        .theme-sunset {
            background: linear-gradient(135deg, #ff6b6b, #feca57);
        }

        .theme-ocean {
            background: linear-gradient(135deg, #00d2ff, #3a7bd5);
        }

        .theme-forest {
            background: linear-gradient(135deg, #11998e, #38ef7d);
        }

        .theme-royal {
            background: linear-gradient(135deg, #8e2de2, #4a00e0);
        }

        .theme-fire {
            background: linear-gradient(135deg, #f12711, #f5af19);
        }

        /* ===== Profile ===== */
        .profile-header {
            text-align: center;
            padding: 30px;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            border-radius: 16px;
            margin-bottom: 20px;
        }

        .profile-avatar {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            background: white;
            margin: 0 auto 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 40px;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.3);
        }

        .profile-stats {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }

        .stat-item {
            text-align: center;
        }

        .stat-number {
            font-size: 24px;
            font-weight: bold;
            display: block;
        }

        .stat-label {
            font-size: 12px;
            color: rgba(255, 255, 255, 0.8);
        }

        /* ===== Search ===== */
        .search-box {
            width: 100%;
            padding: 15px;
            border-radius: 12px;
            background: var(--surface);
            border: 1px solid rgba(102, 126, 234, 0.3);
            color: var(--text);
            font-size: 15px;
            margin-bottom: 20px;
        }

        .user-item {
            display: flex;
            align-items: center;
            gap: 15px;
            padding: 15px;
            background: var(--surface);
            border-radius: 12px;
            margin-bottom: 10px;
            cursor: pointer;
            transition: all 0.3s;
        }

        .user-item:hover {
            transform: translateX(-5px);
            box-shadow: 0 4px 15px rgba(102, 126, 234, 0.3);
        }

        /* ===== Comments ===== */
        .comment-item {
            background: rgba(102, 126, 234, 0.1);
            padding: 15px;
            border-radius: 12px;
            margin-bottom: 10px;
            border-right: 3px solid var(--primary);
        }

        .comment-content {
            margin-bottom: 10px;
        }

        .comment-actions {
            display: flex;
            gap: 10px;
        }

        /* ===== Loading ===== */
        .loading {
            text-align: center;
            padding: 40px;
        }

        .spinner {
            width: 50px;
            height: 50px;
            border: 4px solid rgba(102, 126, 234, 0.2);
            border-top-color: var(--primary);
            border-radius: 50%;
            animation: spin 1s linear infinite;
            margin: 0 auto;
        }

        @keyframes spin {
            to { transform: rotate(360deg); }
        }

        /* ===== Empty State ===== */
        .empty-state {
            text-align: center;
            padding: 60px 20px;
            color: var(--text-secondary);
        }

        .empty-state i {
            font-size: 60px;
            margin-bottom: 20px;
            opacity: 0.5;
        }

        /* ===== Modal ===== */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.8);
            z-index: 2000;
            align-items: center;
            justify-content: center;
        }

        .modal.active {
            display: flex;
        }

        .modal-content {
            background: var(--surface);
            padding: 30px;
            border-radius: 16px;
            max-width: 500px;
            width: 90%;
            max-height: 80vh;
            overflow-y: auto;
        }

        .modal-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }

        .close-btn {
            background: none;
            border: none;
            color: var(--text);
            font-size: 24px;
            cursor: pointer;
        }

        /* ===== Reactions ===== */
        .reactions {
            display: flex;
            gap: 5px;
            flex-wrap: wrap;
        }

        .reaction {
            padding: 5px 10px;
            border-radius: 15px;
            background: rgba(102, 126, 234, 0.2);
            font-size: 14px;
            cursor: pointer;
            transition: all 0.3s;
        }

        .reaction:hover {
            transform: scale(1.2);
        }

        /* ===== Icons (Using Emoji) ===== */
        .icon {
            display: inline-block;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <div class="header">
        <h1>
            <span class="icon">💌</span>
            رسائل مجهولة
        </h1>
    </div>

    <!-- Content -->
    <div class="content">
        <!-- Explore Page -->
        <div id="explore-page" class="page active">
            <div class="input-group">
                <input type="text" id="new-post-input" class="input-field" placeholder="شارك شيئاً مجهولاً... ✨">
                <button onclick="createPost()" class="btn-primary">نشر</button>
            </div>
            
            <div id="posts-container"></div>
        </div>

        <!-- Accounts Page -->
        <div id="accounts-page" class="page">
            <input type="text" id="search-input" class="search-box" placeholder="ابحث عن حساب... 🔍" oninput="searchUsers()">
            <div id="users-container"></div>
        </div>

        <!-- My Profile Page -->
        <div id="profile-page" class="page">
            <div class="profile-header">
                <div class="profile-avatar" id="my-avatar">👤</div>
                <h2 id="my-name">اسمك</h2>
                <p id="my-bio">أضف نبذة عنك...</p>
                <div class="profile-stats">
                    <div class="stat-item">
                        <span class="stat-number" id="posts-count">0</span>
                        <span class="stat-label">منشور</span>
                    </div>
                    <div class="stat-item">
                        <span class="stat-number" id="comments-count">0</span>
                        <span class="stat-label">تعليق</span>
                    </div>
                    <div class="stat-item">
                        <span class="stat-number" id="visitors-count">0</span>
                        <span class="stat-label">زائر</span>
                    </div>
                </div>
            </div>

            <h3 style="margin: 20px 0;">اختر الثيم المفضل 🎨</h3>
            <div class="theme-grid">
                <div class="theme-card theme-default active" onclick="changeTheme('default')">
                    <h4>الافتراضي</h4>
                </div>
                <div class="theme-card theme-sunset" onclick="changeTheme('sunset')">
                    <h4>غروب الشمس</h4>
                </div>
                <div class="theme-card theme-ocean" onclick="changeTheme('ocean')">
                    <h4>المحيط</h4>
                </div>
                <div class="theme-card theme-forest" onclick="changeTheme('forest')">
                    <h4>الغابة</h4>
                </div>
                <div class="theme-card theme-royal" onclick="changeTheme('royal')">
                    <h4>ملكي</h4>
                </div>
                <div class="theme-card theme-fire" onclick="changeTheme('fire')">
                    <h4>النار</h4>
                </div>
            </div>

            <div style="margin-top: 30px;">
                <h3>نبذة عني</h3>
                <textarea id="bio-input" class="input-field" style="width: 100%; min-height: 100px; margin-top: 10px;" placeholder="اكتب نبذة عنك..."></textarea>
                <button onclick="updateBio()" class="btn-primary" style="width: 100%; margin-top: 10px;">حفظ التغييرات</button>
            </div>
        </div>
    </div>

    <!-- Navigation -->
    <div class="nav-tabs">
        <div class="nav-tab active" onclick="switchPage('explore')">
            <i class="icon">🌍</i>
            <span>الاكسبلور</span>
        </div>
        <div class="nav-tab" onclick="switchPage('accounts')">
            <i class="icon">👥</i>
            <span>الحسابات</span>
        </div>
        <div class="nav-tab" onclick="switchPage('profile')">
            <i class="icon">👤</i>
            <span>حسابي</span>
        </div>
    </div>

    <!-- Comments Modal -->
    <div id="comments-modal" class="modal">
        <div class="modal-content">
            <div class="modal-header">
                <h2>التعليقات 💬</h2>
                <button class="close-btn" onclick="closeCommentsModal()">✕</button>
            </div>
            
            <div class="input-group">
                <input type="text" id="comment-input" class="input-field" placeholder="اكتب تعليقاً مجهولاً...">
                <button onclick="addComment()" class="btn-primary">إرسال</button>
            </div>
            
            <div id="comments-container"></div>
        </div>
    </div>

    <script>
        // Telegram WebApp
        let tg = window.Telegram.WebApp;
        tg.expand();
        tg.ready();

        // Global State
        let currentUser = null;
        let currentPostId = null;
        const reactions = ['❤️', '😂', '😮', '😢', '👏', '🔥'];

        // Initialize
        async function init() {
            currentUser = tg.initDataUnsafe.user || {
                id: 123456,
                first_name: 'مستخدم تجريبي'
            };
            
            loadPosts();
            loadUserProfile();
        }

        // Switch Pages
        function switchPage(page) {
            document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
            document.querySelectorAll('.nav-tab').forEach(t => t.classList.remove('active'));
            
            document.getElementById(`${page}-page`).classList.add('active');
            event.currentTarget.classList.add('active');

            if (page === 'explore') loadPosts();
            if (page === 'accounts') loadUsers();
            if (page === 'profile') loadUserProfile();
        }

        // Load Posts
        async function loadPosts() {
            const container = document.getElementById('posts-container');
            container.innerHTML = '<div class="loading"><div class="spinner"></div></div>';

            try {
                const response = await fetch('/api/posts');
                const posts = await response.json();

                if (posts.length === 0) {
                    container.innerHTML = `
                        <div class="empty-state">
                            <i class="icon">📭</i>
                            <h3>لا توجد منشورات بعد</h3>
                            <p>كن أول من ينشر!</p>
                        </div>
                    `;
                    return;
                }

                container.innerHTML = posts.map(post => createPostCard(post)).join('');
            } catch (error) {
                container.innerHTML = '<div class="empty-state"><p>حدث خطأ في تحميل المنشورات</p></div>';
            }
        }

        // Create Post Card
        function createPostCard(post) {
            const totalReactions = Object.values(post.reactions).reduce((a, b) => a + b, 0);
            
            return `
                <div class="post-card">
                    <div class="post-header">
                        <div class="avatar" style="background: ${post.avatar_color || '#667eea'}">
                            ${post.first_name.charAt(0)}
                        </div>
                        <div class="post-info">
                            <h3>${post.first_name}</h3>
                            <span class="post-time">${formatTime(post.created_at)}</span>
                        </div>
                    </div>
                    <div class="post-content">${post.content}</div>
                    <div class="post-actions">
                        <button class="action-btn" onclick="openComments(${post.id})">
                            <span>💬</span>
                            <span>${post.comments_count || 0}</span>
                        </button>
                        <button class="action-btn" onclick="showReactions(${post.id}, 'post')">
                            <span>❤️</span>
                            <span>${totalReactions}</span>
                        </button>
                    </div>
                    <div class="reactions">
                        ${reactions.map(r => `<span class="reaction" onclick="addReaction(${post.id}, 'post', '${r}')">${r}</span>`).join('')}
                    </div>
                </div>
            `;
        }

        // Create Post
        async function createPost() {
            const input = document.getElementById('new-post-input');
            const content = input.value.trim();

            if (!content) {
                tg.showAlert('الرجاء كتابة شيء أولاً!');
                return;
            }

            try {
                await fetch('/api/post', {
                    method: 'POST',
                    headers: {'Content-Type': 'application/json'},
                    body: JSON.stringify({
                        user_id: currentUser.id,
                        content: content,
                        type: 'message'
                    })
                });

                input.value = '';
                loadPosts();
                tg.showAlert('تم النشر بنجاح! ✨');
            } catch (error) {
                tg.showAlert('حدث خطأ في النشر');
            }
        }

        // Open Comments Modal
        async function openComments(postId) {
            currentPostId = postId;
            document.getElementById('comments-modal').classList.add('active');
            
            const container = document.getElementById('comments-container');
            container.innerHTML = '<div class="loading"><div class="spinner"></div></div>';

            try {
                const response = await fetch(`/api/post/${postId}/comments`);
                const comments = await response.json();

                if (comments.length === 0) {
                    container.innerHTML = `
                        <div class="empty-state">
                            <i class="icon">💬</i>
                            <p>لا توجد تعليقات بعد. كن أول من يعلق!</p>
                        </div>
                    `;
                    return;
                }

                container.innerHTML = comments.map(comment => `
                    <div class="comment-item">
                        <div class="comment-content">${comment.content}</div>
                        <div class="comment-actions">
                            ${reactions.map(r => `<span class="reaction" onclick="addReaction(${comment.id}, 'comment', '${r}')">${r}</span>`).join('')}
                        </div>
                    </div>
                `).join('');
            } catch (error) {
                container.innerHTML = '<div class="empty-state"><p>حدث خطأ في تحميل التعليقات</p></div>';
            }
        }

        // Add Comment
        async function addComment() {
            const input = document.getElementById('comment-input');
            const content = input.value.trim();

            if (!content) return;

            try {
                await fetch('/api/comment', {
                    method: 'POST',
                    headers: {'Content-Type': 'application/json'},
                    body: JSON.stringify({
                        post_id: currentPostId,
                        content: content
                    })
                });

                input.value = '';
                openComments(currentPostId);
            } catch (error) {
                tg.showAlert('حدث خطأ في إضافة التعليق');
            }
        }

        // Close Comments Modal
        function closeCommentsModal() {
            document.getElementById('comments-modal').classList.remove('active');
            loadPosts();
        }

        // Add Reaction
        async function addReaction(id, type, reaction) {
            try {
                await fetch('/api/react', {
                    method: 'POST',
                    headers: {'Content-Type': 'application/json'},
                    body: JSON.stringify({
                        id: id,
                        type: type,
                        reaction: reaction
                    })
                });

                if (type === 'post') {
                    loadPosts();
                } else {
                    openComments(currentPostId);
                }
            } catch (error) {
                console.error('Error adding reaction:', error);
            }
        }

        // Search Users
        async function searchUsers() {
            const query = document.getElementById('search-input').value;
            
            if (query.length < 2) {
                loadUsers();
                return;
            }

            const container = document.getElementById('users-container');
            
            try {
                const response = await fetch(`/api/search?q=${encodeURIComponent(query)}`);
                const users = await response.json();

                if (users.length === 0) {
                    container.innerHTML = `
                        <div class="empty-state">
                            <i class="icon">🔍</i>
                            <p>لم يتم العثور على نتائج</p>
                        </div>
                    `;
                    return;
                }

                container.innerHTML = users.map(user => `
                    <div class="user-item" onclick="viewUserProfile(${user.user_id})">
                        <div class="avatar" style="background: ${user.avatar_color}">
                            ${user.first_name.charAt(0)}
                        </div>
                        <div>
                            <h3>${user.first_name}</h3>
                            <p style="color: var(--text-secondary); font-size: 14px;">@${user.username || 'user'}</p>
                        </div>
                    </div>
                `).join('');
            } catch (error) {
                container.innerHTML = '<div class="empty-state"><p>حدث خطأ</p></div>';
            }
        }

        // Load Users
        async function loadUsers() {
            const container = document.getElementById('users-container');
            container.innerHTML = '<div class="loading"><div class="spinner"></div></div>';

            try {
                const response = await fetch('/api/posts');
                const posts = await response.json();
                
                const uniqueUsers = [...new Map(posts.map(p => [p.user_id, p])).values()];

                container.innerHTML = uniqueUsers.map(user => `
                    <div class="user-item" onclick="viewUserProfile(${user.user_id})">
                        <div class="avatar" style="background: ${user.avatar_color}">
                            ${user.first_name.charAt(0)}
                        </div>
                        <div>
                            <h3>${user.first_name}</h3>
                            <p style="color: var(--text-secondary); font-size: 14px;">@${user.username || 'user'}</p>
                        </div>
                    </div>
                `).join('');
            } catch (error) {
                container.innerHTML = '<div class="empty-state"><p>حدث خطأ</p></div>';
            }
        }

        // Load User Profile
        async function loadUserProfile() {
            try {
                const response = await fetch(`/api/user/${currentUser.id}`);
                const user = await response.json();

                document.getElementById('my-name').textContent = user.first_name;
                document.getElementById('my-bio').textContent = user.bio || 'أضف نبذة عنك...';
                document.getElementById('my-avatar').textContent = user.first_name.charAt(0);
                document.getElementById('posts-count').textContent = user.posts?.length || 0;
                document.getElementById('bio-input').value = user.bio || '';
            } catch (error) {
                console.error('Error loading profile:', error);
            }
        }

        // Change Theme
        async function changeTheme(theme) {
            document.querySelectorAll('.theme-card').forEach(t => t.classList.remove('active'));
            event.currentTarget.classList.add('active');

            const themes = {
                'default': ['#667eea', '#764ba2'],
                'sunset': ['#ff6b6b', '#feca57'],
                'ocean': ['#00d2ff', '#3a7bd5'],
                'forest': ['#11998e', '#38ef7d'],
                'royal': ['#8e2de2', '#4a00e0'],
                'fire': ['#f12711', '#f5af19']
            };

            const colors = themes[theme];
            document.documentElement.style.setProperty('--primary', colors[0]);
            document.documentElement.style.setProperty('--secondary', colors[1]);

            try {
                await fetch(`/api/user/${currentUser.id}/update`, {
                    method: 'POST',
                    headers: {'Content-Type': 'application/json'},
                    body: JSON.stringify({
                        theme: theme,
                        avatar_color: colors[0]
                    })
                });
            } catch (error) {
                console.error('Error updating theme:', error);
            }
        }

        // Update Bio
        async function updateBio() {
            const bio = document.getElementById('bio-input').value;

            try {
                await fetch(`/api/user/${currentUser.id}/update`, {
                    method: 'POST',
                    headers: {'Content-Type': 'application/json'},
                    body: JSON.stringify({ bio: bio })
                });

                tg.showAlert('تم حفظ التغييرات بنجاح! ✨');
                loadUserProfile();
            } catch (error) {
                tg.showAlert('حدث خطأ في الحفظ');
            }
        }

        // Format Time
        function formatTime(timestamp) {
            const date = new Date(timestamp);
            const now = new Date();
            const diff = Math.floor((now - date) / 1000);

            if (diff < 60) return 'الآن';
            if (diff < 3600) return `منذ ${Math.floor(diff / 60)} دقيقة`;
            if (diff < 86400) return `منذ ${Math.floor(diff / 3600)} ساعة`;
            return `منذ ${Math.floor(diff / 86400)} يوم`;
        }

        // Initialize App
        init();
    </script>
</body>
</html>