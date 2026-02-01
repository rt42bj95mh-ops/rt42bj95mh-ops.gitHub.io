<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>山西省晋北畅行交通文化社 - 重载铁路技术交流社区</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+SC:wght@300;400;500;700;900&family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --rail-red: #8B0000;
            --coal-gray: #1f1f1f;
            --gold: #DAA520;
        }
        
        body {
            background-color: #0f0f0f;
            background-image: linear-gradient(rgba(139, 0, 0, 0.03) 1px, transparent 1px),
                              linear-gradient(90deg, rgba(139, 0, 0, 0.03) 1px, transparent 1px);
            background-size: 20px 20px;
            color: #d4d4d4;
            font-family: 'Noto Sans SC', sans-serif;
        }
        
        /* 权限系统 */
        body.president-mode .president-only { display: flex !important; }
        body.president-mode .president-inline { display: inline-flex !important; }
        body.president-mode .president-block { display: block !important; }
        .president-only, .president-inline, .president-block { display: none !important; }
        .author-only { display: none !important; }
        .thread-row[data-is-author="true"] .author-only { display: inline-flex !important; }
        
        /* 按钮样式 */
        .btn-metal { 
            background: linear-gradient(to bottom, #4a4a4a 0%, #2d2d2d 50%, #1f1f1f 100%); 
            border: 1px solid #555; 
            box-shadow: 0 2px 4px rgba(0,0,0,0.5);
            transition: all 0.2s;
        }
        .btn-metal:hover { border-color: #777; transform: translateY(-1px); }
        
        .btn-red { 
            background: linear-gradient(to bottom, #a52a2a 0%, #8B0000 50%, #6b0000 100%); 
            border: 1px solid #a52a2a; 
            color: white;
            transition: all 0.2s;
        }
        .btn-red:hover { filter: brightness(1.2); }
        
        .btn-gold {
            background: linear-gradient(to bottom, #DAA520 0%, #B8860B 100%);
            border: 1px solid #DAA520;
            color: #000;
            font-weight: bold;
        }
        
        .btn-shop {
            background: linear-gradient(135deg, #2a2a2a, #1f1f1f);
            border: 1px solid #444;
            color: #DAA520;
            transition: all 0.3s;
        }
        .btn-shop:hover {
            border-color: #DAA520;
            box-shadow: 0 0 15px rgba(218,165,32,0.3);
            transform: translateY(-2px);
        }
        
        /* 论坛表格 */
        .forum-table { border: 1px solid #333; box-shadow: 0 4px 6px rgba(0,0,0,0.5); }
        .forum-header { background: linear-gradient(to bottom, #2a2a2a, #1a1a1a); border-bottom: 2px solid #8B0000; }
        .forum-row { 
            background: linear-gradient(to bottom, #252525, #1e1e1e); 
            border-bottom: 1px solid #333; 
            transition: all 0.3s ease;
        }
        .forum-row:hover { 
            background: linear-gradient(to bottom, #2a2a2a, #222); 
        }
        .forum-row.expanded { 
            background: linear-gradient(to bottom, #1e1e1e, #1a1a1a); 
            box-shadow: inset 0 2px 8px rgba(0,0,0,0.5);
        }
        .sticky-top { background: linear-gradient(to right, rgba(218, 165, 32, 0.1), transparent); border-left: 3px solid #DAA520; }
        
        /* 帖子内容展开区域 */
        .post-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.4s ease-out, padding 0.3s ease;
            opacity: 0;
        }
        .post-content.expanded {
            max-height: 1000px;
            opacity: 1;
            padding-top: 1rem;
            margin-top: 0.5rem;
            border-top: 1px solid #333;
        }
        .post-content-text {
            color: #ccc;
            line-height: 1.8;
            font-size: 0.95rem;
            white-space: pre-wrap;
            word-wrap: break-word;
        }
        
        /* 商城商品卡片 */
        .shop-item {
            background: linear-gradient(135deg, #1f1f1f, #2a2a2a);
            border: 1px solid #333;
            transition: all 0.3s;
            position: relative;
            overflow: hidden;
        }
        .shop-item:hover {
            border-color: #DAA520;
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(0,0,0,0.5), 0 0 20px rgba(218,165,32,0.1);
        }
        .shop-item::before {
            content: '';
            position: absolute;
            top: 0; left: -100%;
            width: 100%; height: 100%;
            background: linear-gradient(90deg, transparent, rgba(218,165,32,0.1), transparent);
            transition: left 0.5s;
        }
        .shop-item:hover::before { left: 100%; }
        
        /* 头像框效果 */
        .avatar-frame-gold { border: 3px solid #DAA520; box-shadow: 0 0 15px rgba(218,165,32,0.5); }
        .avatar-frame-silver { border: 3px solid #C0C0C0; box-shadow: 0 0 10px rgba(192,192,192,0.3); }
        .avatar-frame-bronze { border: 3px solid #CD7F32; box-shadow: 0 0 10px rgba(205,127,50,0.3); }
        .avatar-frame-rail { border: 3px solid #8B0000; box-shadow: 0 0 10px rgba(139,0,0,0.4); }
        
        /* 用户名特效 */
        .name-gold { color: #DAA520; text-shadow: 0 0 10px rgba(218,165,32,0.4); }
        .name-red { color: #ff4444; text-shadow: 0 0 8px rgba(255,68,68,0.3); }
        .name-blue { color: #4169E1; text-shadow: 0 0 8px rgba(65,105,225,0.3); }
        
        /* 勋章 */
        .badge {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 20px;
            height: 20px;
            border-radius: 50%;
            font-size: 12px;
            margin-left: 4px;
            cursor: help;
            position: relative;
        }
        .badge:hover::after {
            content: attr(data-title);
            position: absolute;
            bottom: 100%;
            left: 50%;
            transform: translateX(-50%);
            background: #000;
            color: #fff;
            padding: 4px 8px;
            border-radius: 4px;
            font-size: 11px;
            white-space: nowrap;
            border: 1px solid #444;
            z-index: 100;
        }
        
        /* 积分动画 */
        @keyframes pointsFloat {
            0% { transform: translateY(0); opacity: 1; }
            100% { transform: translateY(-30px); opacity: 0; }
        }
        .points-float {
            position: fixed;
            color: #DAA520;
            font-weight: bold;
            font-size: 18px;
            pointer-events: none;
            animation: pointsFloat 1s ease-out forwards;
            z-index: 9999;
            text-shadow: 0 0 10px rgba(218,165,32,0.8);
        }
        
        /* 背包物品 */
        .inventory-item {
            background: rgba(0,0,0,0.3);
            border: 1px solid #444;
            transition: all 0.2s;
        }
        .inventory-item:hover { border-color: #DAA520; }
        .inventory-item.equipped { 
            border-color: #DAA520; 
            background: rgba(218,165,32,0.1);
            box-shadow: 0 0 10px rgba(218,165,32,0.2);
        }
        
        .stat-number { font-family: 'JetBrains Mono', monospace; color: #DAA520; }
        .hidden-trigger { position: fixed; bottom: 0; right: 0; width: 10px; height: 10px; opacity: 0; z-index: 9999; }
        
        ::-webkit-scrollbar { width: 10px; background: #0f0f0f; }
        ::-webkit-scrollbar-thumb { background: #333; border: 1px solid #444; }
        
        .modal-enter { animation: modalSlide 0.3s ease-out; }
        @keyframes modalSlide { from { opacity: 0; transform: translateY(-20px); } to { opacity: 1; transform: translateY(0); } }
        
        /* 展开/收起指示器 */
        .expand-indicator {
            transition: transform 0.3s ease;
        }
        .expanded .expand-indicator {
            transform: rotate(180deg);
        }
    </style>
</head>
<body class="min-h-screen flex flex-col">

    <div class="hidden-trigger" id="president-trigger" onclick="handleSecretTrigger()"></div>

    <!-- 顶部栏 -->
    <div class="bg-[#151515] border-b border-[#333] text-xs py-2 px-4">
        <div class="max-w-7xl mx-auto flex justify-between items-center">
            <div class="flex items-center gap-4">
                <span class="text-gray-500">北京时间: <span class="text-[#DAA520] font-mono" id="beijing-time">--:--:--</span></span>
                <span class="text-gray-600">|</span>
                <span class="text-gray-500 text-[10px] opacity-60"><i class="fas fa-shield-alt mr-1"></i>系统安全维护中</span>
            </div>
            <div class="flex items-center gap-4">
                <span>帖子: <span class="stat-number" id="stat-posts">0</span></span>
                <span>会员: <span class="stat-number">1,247</span></span>
                <span>在线: <span class="stat-number text-green-500">56</span></span>
            </div>
        </div>
    </div>

    <!-- 导航 -->
    <nav class="sticky top-0 z-50 bg-[#1f1f1f] border-b-2 border-[#8B0000] shadow-lg">
        <div class="max-w-7xl mx-auto flex items-center h-14 px-4">
            <div class="flex items-center gap-2 mr-8 cursor-pointer" onclick="if(DB.currentUser && DB.currentUser.role === 'president') location.reload()">
                <i class="fas fa-train text-[#8B0000] text-xl"></i>
                <span class="font-black text-white text-lg tracking-wider">晋北畅行</span>
                <span class="president-only ml-2 px-2 py-0.5 bg-[#DAA520] text-black text-[10px] font-bold rounded hidden">管理</span>
            </div>
            
            <div class="hidden md:flex items-center gap-1">
                <a href="#" class="px-4 py-2 text-gray-300 hover:text-white hover:bg-white/5 rounded transition-colors">首页</a>
                <a href="#" class="px-4 py-2 text-gray-300 hover:text-white hover:bg-white/5 rounded transition-colors">技术区</a>
                <a href="#" class="px-4 py-2 text-gray-300 hover:text-white hover:bg-white/5 rounded transition-colors">摄影区</a>
                <button onclick="openShop()" class="px-4 py-2 text-[#DAA520] hover:text-[#FFD700] transition-colors font-medium relative">
                    <i class="fas fa-store mr-1"></i>积分商城
                    <span class="absolute -top-1 -right-1 w-2 h-2 bg-red-500 rounded-full animate-pulse"></span>
                </button>
                <button onclick="showRules()" class="px-4 py-2 text-[#8B0000] hover:text-[#ff0000] transition-colors font-medium">
                    <i class="fas fa-gavel mr-1"></i>社区法规
                </button>
            </div>
            
            <div class="flex-1"></div>
            
            <div id="user-area" class="flex items-center gap-3">
                <div id="guest-state">
                    <button onclick="showAuth()" class="btn-metal px-4 py-1.5 rounded text-sm text-white">登录 / 注册</button>
                </div>
                <div id="user-state" class="hidden flex items-center gap-3">
                    <div class="flex items-center gap-2 bg-[#0f0f0f] border border-[#333] px-3 py-1.5 rounded-full cursor-pointer hover:border-[#DAA520] transition-colors" onclick="openShop()">
                        <i class="fas fa-coins text-[#DAA520]"></i>
                        <span id="nav-points" class="text-[#DAA520] font-bold text-sm">0</span>
                    </div>
                    <div class="relative group">
                        <img id="user-avatar" src="" class="w-8 h-8 rounded-full border-2 border-[#444] group-hover:border-[#DAA520] transition-all cursor-pointer object-cover bg-[#333]" onclick="openAvatarModal()" title="点击更换头像">
                        <div class="absolute inset-0 bg-black/50 rounded-full opacity-0 group-hover:opacity-100 flex items-center justify-center cursor-pointer transition-opacity" onclick="openAvatarModal()">
                            <i class="fas fa-camera text-white text-xs"></i>
                        </div>
                    </div>
                    <span id="nav-username" class="font-bold text-sm"></span>
                    <button onclick="logout()" class="text-gray-500 hover:text-white text-sm"><i class="fas fa-sign-out-alt"></i></button>
                </div>
            </div>
        </div>
    </nav>

    <!-- 会长管理条 -->
    <div class="president-only bg-gradient-to-r from-[#1f1f1f] via-[#2a2000] to-[#1f1f1f] border-b border-[#DAA520]/30 px-4 py-2 hidden">
        <div class="max-w-7xl mx-auto flex items-center justify-between text-xs">
            <div class="flex items-center gap-4 text-[#DAA520]">
                <span><i class="fas fa-crown mr-1"></i>最高管理权限已激活</span>
                <span>|</span>
                <span>无限积分模式 | 您可以修改、删除全站任何内容，发放/扣除积分</span>
            </div>
            <div class="flex gap-3">
                <button onclick="managePoints()" class="text-[#DAA520] hover:text-[#FFD700]"><i class="fas fa-coins mr-1"></i>积分管理</button>
                <button onclick="viewAuditLog()" class="text-gray-400 hover:text-white"><i class="fas fa-clipboard-list mr-1"></i>审核日志</button>
            </div>
        </div>
    </div>

    <!-- 主内容 -->
    <main class="flex-1 max-w-7xl mx-auto w-full p-4 grid grid-cols-1 lg:grid-cols-4 gap-6 mt-4">
        
        <!-- 左侧内容区 -->
        <div class="lg:col-span-3 space-y-4">
            <!-- 置顶区 -->
            <div class="forum-table rounded-lg overflow-hidden">
                <div class="forum-header px-4 py-3 bg-[#2a2a2a] flex justify-between items-center">
                    <h2 class="font-bold text-white flex items-center gap-2"><i class="fas fa-thumbtack text-[#DAA520]"></i>公告区</h2>
                    <span class="text-xs text-gray-500">版主: 管理员</span>
                </div>
                <div id="sticky-list" class="divide-y divide-[#333]"></div>
            </div>

            <!-- 操作栏 -->
            <div class="flex flex-wrap items-center justify-between gap-3 bg-[#1a1a1a] p-3 rounded-lg border border-[#333]">
                <div class="flex items-center gap-2">
                    <select id="filter-sort" class="bg-[#0f0f0f] border border-[#444] text-gray-300 text-sm rounded px-3 py-1.5">
                        <option value="new">最新发布</option>
                        <option value="hot">热度最高</option>
                        <option value="essence">精华帖</option>
                    </select>
                </div>
                <button onclick="openPostModal()" class="btn-red px-4 py-1.5 rounded text-sm font-bold flex items-center gap-2">
                    <i class="fas fa-plus"></i>发布帖子
                </button>
            </div>

            <!-- 帖子列表 -->
            <div class="forum-table rounded-lg overflow-hidden" id="thread-container">
                <div class="forum-header px-4 py-3">
                    <h2 class="font-bold text-white">讨论区</h2>
                </div>
                <div id="thread-list" class="divide-y divide-[#333]"></div>
            </div>
        </div>

        <!-- 侧边栏 -->
        <aside class="space-y-4">
            <!-- 快捷入口 -->
            <div class="bg-gradient-to-br from-[#1f1f1f] to-[#2a0000] border border-[#8B0000]/30 rounded-lg p-4 shadow-lg">
                <h3 class="font-bold text-white mb-4 flex items-center gap-2">
                    <i class="fas fa-bolt text-[#DAA520]"></i>快捷通道
                </h3>
                <div class="grid grid-cols-2 gap-3">
                    <button onclick="openShop()" class="btn-shop py-3 rounded flex flex-col items-center gap-1 group">
                        <i class="fas fa-store text-2xl group-hover:scale-110 transition-transform"></i>
                        <span class="text-xs">积分商城</span>
                    </button>
                    <button onclick="openInventory()" class="btn-shop py-3 rounded flex flex-col items-center gap-1 group">
                        <i class="fas fa-box-open text-2xl group-hover:scale-110 transition-transform"></i>
                        <span class="text-xs">我的背包</span>
                    </button>
                </div>
            </div>

            <!-- 个人信息 -->
            <div id="sidebar-profile" class="hidden bg-[#1a1a1a] border border-[#333] rounded-lg p-4">
                <div class="flex items-center gap-3 mb-4">
                    <div class="relative group cursor-pointer" onclick="openAvatarModal()">
                        <img id="sidebar-avatar" src="" class="w-16 h-16 rounded-full border-2 border-[#444] group-hover:border-[#DAA520] transition-all object-cover bg-[#333]" alt="">
                        <div id="sidebar-frame" class="absolute inset-0 rounded-full pointer-events-none"></div>
                        <div class="absolute inset-0 bg-black/60 rounded-full opacity-0 group-hover:opacity-100 flex items-center justify-center transition-opacity">
                            <i class="fas fa-camera text-[#DAA520] text-lg"></i>
                        </div>
                    </div>
                    <div class="flex-1">
                        <div id="sidebar-username" class="font-bold text-white flex items-center gap-1"></div>
                        <div id="sidebar-role" class="text-xs text-gray-500 mb-1"></div>
                        <div class="flex items-center gap-2 text-[#DAA520] text-sm font-bold bg-[#0f0f0f] px-2 py-1 rounded w-fit border border-[#333]">
                            <i class="fas fa-coins"></i>
                            <span id="sidebar-points">0</span>
                        </div>
                    </div>
                </div>
                <div class="grid grid-cols-2 gap-2 text-center text-xs">
                    <div class="bg-[#0f0f0f] p-2 rounded border border-[#333]">
                        <div class="text-[#DAA520] font-bold" id="user-post-count">0</div>
                        <div class="text-gray-500">我的帖子</div>
                    </div>
                    <div class="bg-[#0f0f0f] p-2 rounded border border-[#333] cursor-pointer hover:border-[#DAA520] transition-colors" onclick="openInventory()">
                        <div class="text-[#DAA520] font-bold" id="user-item-count">0</div>
                        <div class="text-gray-500">装饰品</div>
                    </div>
                </div>
                <button onclick="openShop()" class="w-full mt-3 btn-gold py-2 rounded text-sm font-bold flex items-center justify-center gap-2">
                    <i class="fas fa-shopping-cart"></i>去商城兑换
                </button>
            </div>

            <!-- 获取积分方式 -->
            <div class="bg-[#1a1a1a] border border-[#333] rounded-lg p-4">
                <h3 class="font-bold text-white mb-3 text-sm flex items-center gap-2">
                    <i class="fas fa-info-circle text-[#8B0000]"></i>如何获得积分？
                </h3>
                <ul class="space-y-2 text-xs text-gray-400">
                    <li class="flex justify-between items-center bg-[#0f0f0f] p-2 rounded">
                        <span><i class="fas fa-file-alt mr-1 text-gray-500"></i>发布帖子</span>
                        <span class="text-[#DAA520] font-bold">+10</span>
                    </li>
                    <li class="flex justify-between items-center bg-[#0f0f0f] p-2 rounded">
                        <span><i class="fas fa-check-circle mr-1 text-gray-500"></i>每日签到</span>
                        <span class="text-[#DAA520] font-bold">+5</span>
                    </li>
                    <li class="flex justify-between items-center bg-[#0f0f0f] p-2 rounded">
                        <span><i class="fas fa-gift mr-1 text-gray-500"></i>收到打赏</span>
                        <span class="text-[#DAA520] font-bold">+1/10积分</span>
                    </li>
                    <li class="flex justify-between items-center bg-[#0f0f0f] p-2 rounded">
                        <span><i class="fas fa-gem mr-1 text-gray-500"></i>帖子加精</span>
                        <span class="text-[#DAA520] font-bold">+50</span>
                    </li>
                </ul>
            </div>
        </aside>
    </main>

    <!-- ================= 模态框 ================= -->

    <!-- 打赏模态框 -->
    <div id="reward-modal" class="hidden fixed inset-0 z-[1002] bg-black/95 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-[#1f1f1f] border border-[#DAA520] rounded-lg w-full max-w-md modal-enter relative">
            <div class="bg-gradient-to-r from-[#2a2000] to-[#1f1f1f] p-4 border-b border-[#DAA520]/30 flex justify-between items-center">
                <h3 class="font-bold text-[#DAA520] flex items-center gap-2">
                    <i class="fas fa-gift"></i>打赏帖子
                </h3>
                <button onclick="closeRewardModal()" class="text-gray-400 hover:text-white">
                    <i class="fas fa-times"></i>
                </button>
            </div>
            <div class="p-6 space-y-4">
                <div class="text-center">
                    <p class="text-gray-400 text-sm mb-1">向作者 <span id="reward-target-name" class="text-[#DAA520] font-bold"></span> 打赏</p>
                    <p class="text-xs text-gray-500">打赏10积分，对方获得1积分（类似B站投币机制）</p>
                </div>
                
                <div class="grid grid-cols-4 gap-2 mb-2">
                    <button onclick="selectRewardAmount(10)" class="reward-btn bg-[#0f0f0f] border border-[#444] hover:border-[#DAA520] text-white py-2 rounded text-sm transition-colors" data-amount="10">
                        <div class="text-[#DAA520] font-bold">10</div>
                        <div class="text-[10px] text-gray-500">积分</div>
                    </button>
                    <button onclick="selectRewardAmount(20)" class="reward-btn bg-[#0f0f0f] border border-[#444] hover:border-[#DAA520] text-white py-2 rounded text-sm transition-colors" data-amount="20">
                        <div class="text-[#DAA520] font-bold">20</div>
                        <div class="text-[10px] text-gray-500">积分</div>
                    </button>
                    <button onclick="selectRewardAmount(50)" class="reward-btn bg-[#0f0f0f] border border-[#444] hover:border-[#DAA520] text-white py-2 rounded text-sm transition-colors" data-amount="50">
                        <div class="text-[#DAA520] font-bold">50</div>
                        <div class="text-[10px] text-gray-500">积分</div>
                    </button>
                    <button onclick="selectRewardAmount(100)" class="reward-btn bg-[#0f0f0f] border border-[#444] hover:border-[#DAA520] text-white py-2 rounded text-sm transition-colors" data-amount="100">
                        <div class="text-[#DAA520] font-bold">100</div>
                        <div class="text-[10px] text-gray-500">积分</div>
                    </button>
                </div>
                
                <div class="bg-[#0f0f0f] p-3 rounded border border-[#333]">
                    <div class="text-xs text-gray-400 mb-2">自定义金额（10的倍数）</div>
                    <input type="number" id="reward-custom-amount" placeholder="输入积分数量" min="10" step="10" 
                           class="w-full bg-[#1a1a1a] border border-[#444] rounded px-3 py-2 text-white text-sm focus:border-[#DAA520] outline-none">
                </div>
                
                <div class="bg-[#0f0f0f] p-3 rounded border border-[#333] text-xs space-y-1">
                    <div class="flex justify-between text-gray-400">
                        <span>您将支付:</span>
                        <span class="text-white font-bold" id="reward-pay">0 积分</span>
                    </div>
                    <div class="flex justify-between text-gray-400">
                        <span>作者获得:</span>
                        <span class="text-[#DAA520] font-bold" id="reward-get">0 积分</span>
                    </div>
                    <div class="flex justify-between text-[10px] text-gray-600 pt-1 border-t border-[#333]">
                        <span>平台服务费(90%):</span>
                        <span id="reward-fee">0 积分</span>
                    </div>
                </div>
                
                <button onclick="submitReward()" id="reward-submit-btn" class="w-full btn-gold py-3 rounded text-sm font-bold opacity-50 cursor-not-allowed" disabled>
                    确认打赏
                </button>
            </div>
        </div>
    </div>

    <!-- 积分商城模态框 -->
    <div id="shop-modal" class="hidden fixed inset-0 z-[1001] bg-black/95 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-[#1f1f1f] border border-[#444] rounded-lg w-full max-w-4xl h-[85vh] flex flex-col modal-enter">
            <div class="flex items-center justify-between p-4 border-b border-[#444] bg-gradient-to-r from-[#1f1f1f] to-[#2a2000]">
                <div class="flex items-center gap-3">
                    <i class="fas fa-store text-[#DAA520] text-2xl"></i>
                    <div>
                        <h3 class="font-bold text-white text-lg">积分商城</h3>
                        <p class="text-xs text-gray-500">使用积分兑换装饰品，彰显您的身份</p>
                    </div>
                </div>
                <div class="flex items-center gap-4">
                    <div class="bg-[#0f0f0f] border border-[#DAA520] px-4 py-2 rounded-full flex items-center gap-2">
                        <i class="fas fa-coins text-[#DAA520]"></i>
                        <span class="text-[#DAA520] font-bold" id="shop-points">0</span>
                        <span class="text-xs text-gray-500">积分</span>
                    </div>
                    <button onclick="closeShop()" class="text-gray-500 hover:text-white w-8 h-8 flex items-center justify-center rounded-full hover:bg-white/10">
                        <i class="fas fa-times"></i>
                    </button>
                </div>
            </div>
            
            <div class="flex flex-1 overflow-hidden">
                <!-- 商品列表 -->
                <div class="flex-1 overflow-y-auto p-6">
                    <div class="grid grid-cols-2 md:grid-cols-3 gap-4" id="shop-items">
                        <!-- 动态生成商品 -->
                    </div>
                </div>
                
                <!-- 我的背包侧边栏 -->
                <div class="w-64 border-l border-[#333] bg-[#1a1a1a] p-4 overflow-y-auto" id="inventory-panel">
                    <h4 class="font-bold text-white mb-3 flex items-center gap-2">
                        <i class="fas fa-box text-[#DAA520]"></i>我的背包
                    </h4>
                    <div id="inventory-list" class="space-y-2">
                        <p class="text-xs text-gray-500 text-center py-4">暂无装饰品</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- 我的背包模态框（独立入口） -->
    <div id="inventory-modal" class="hidden fixed inset-0 z-[1000] bg-black/90 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-[#1f1f1f] border border-[#444] rounded-lg w-full max-w-2xl modal-enter">
            <div class="flex items-center justify-between p-4 border-b border-[#444]">
                <h3 class="font-bold text-white flex items-center gap-2"><i class="fas fa-box-open text-[#DAA520]"></i>我的背包</h3>
                <button onclick="closeInventory()" class="text-gray-500 hover:text-white"><i class="fas fa-times"></i></button>
            </div>
            <div class="p-6">
                <div id="inventory-detail-list" class="grid grid-cols-3 gap-4">
                    <!-- 动态生成 -->
                </div>
                <div class="mt-6 pt-4 border-t border-[#333]">
                    <h4 class="text-sm font-bold text-white mb-2">当前装扮预览</h4>
                    <div class="flex items-center gap-4 bg-[#0f0f0f] p-4 rounded border border-[#333]">
                        <div class="relative">
                            <img id="preview-avatar" src="" class="w-16 h-16 rounded-full object-cover bg-[#333]">
                            <div id="preview-frame" class="absolute inset-0 rounded-full pointer-events-none"></div>
                        </div>
                        <div>
                            <div id="preview-username" class="font-bold"></div>
                            <div id="preview-badges" class="flex gap-1 mt-1"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- 头像上传模态框 -->
    <div id="avatar-modal" class="hidden fixed inset-0 z-[1000] bg-black/95 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-[#1f1f1f] border border-[#444] rounded-lg w-full max-w-md modal-enter">
            <div class="flex items-center justify-between p-4 border-b border-[#444]">
                <h3 class="font-bold text-white"><i class="fas fa-user-circle text-[#DAA520] mr-2"></i>更换头像</h3>
                <button onclick="closeAvatarModal()" class="text-gray-500 hover:text-white"><i class="fas fa-times"></i></button>
            </div>
            <div class="p-6 space-y-4">
                <div class="flex justify-center mb-4">
                    <img id="avatar-current-preview" src="" class="w-24 h-24 rounded-full border-4 border-[#444] object-cover bg-[#333]">
                </div>
                <div id="avatar-upload-zone" class="border-2 border-dashed border-[#444] rounded-lg p-8 text-center cursor-pointer hover:border-[#8B0000] transition-colors relative">
                    <input type="file" id="avatar-input" accept="image/jpeg,image/png,image/gif" class="absolute inset-0 w-full h-full opacity-0 cursor-pointer" onchange="handleAvatarSelect(event)">
                    <i class="fas fa-cloud-upload-alt text-3xl text-[#444] mb-2"></i>
                    <p class="text-gray-400 text-sm">点击或拖拽上传头像</p>
                    <p class="text-gray-600 text-xs mt-1">支持 JPG、PNG、GIF，最大 2MB</p>
                </div>
                <div id="avatar-new-preview-container" class="hidden text-center">
                    <img id="avatar-new-preview" src="" class="w-20 h-20 rounded-full border-2 border-[#DAA520] object-cover mx-auto">
                    <p class="text-xs text-gray-400 mt-2">新头像预览</p>
                </div>
                <div class="flex gap-3">
                    <button onclick="closeAvatarModal()" class="flex-1 btn-metal py-2 rounded text-sm">取消</button>
                    <button onclick="saveAvatar()" id="avatar-save-btn" class="flex-1 btn-red py-2 rounded text-sm font-bold opacity-50" disabled>保存</button>
                </div>
            </div>
        </div>
    </div>

    <!-- 登录/注册模态框 -->
    <div id="auth-modal" class="hidden fixed inset-0 z-[1000] bg-black/90 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-[#1f1f1f] border border-[#444] rounded-lg w-full max-w-md modal-enter relative">
            <div class="flex border-b border-[#444]">
                <button onclick="switchAuth('login')" id="auth-tab-login" class="flex-1 py-3 text-center font-bold bg-[#8B0000] text-white">登录</button>
                <button onclick="switchAuth('register')" id="auth-tab-reg" class="flex-1 py-3 text-center font-bold text-gray-400 hover:bg-[#2a2a2a]">注册</button>
            </div>
            <div class="p-6 space-y-4">
                <div id="auth-login-panel">
                    <div class="space-y-3">
                        <input type="text" id="login-user" placeholder="用户名" class="w-full bg-[#0f0f0f] border border-[#444] rounded px-3 py-2 text-white focus:border-[#8B0000] outline-none">
                        <input type="password" id="login-pass" placeholder="密码" class="w-full bg-[#0f0f0f] border border-[#444] rounded px-3 py-2 text-white focus:border-[#8B0000] outline-none">
                        <div class="p-3 bg-[#1a1a1a] border border-[#333] rounded">
                            <div class="text-xs text-gray-400 mb-2">安全验证 - 密保答案</div>
                            <select id="login-question" class="w-full bg-[#0f0f0f] border border-[#444] rounded px-2 py-1.5 text-sm text-gray-300 mb-2">
                                <option value="1">您母亲的姓名是？</option>
                                <option value="2">您的第一辆模型车是？</option>
                                <option value="3">您最喜爱的机车型号是？</option>
                                <option value="president" class="hidden" id="president-question">管理员专用验证通道</option>
                            </select>
                            <input type="password" id="login-security" placeholder="密保答案" class="w-full bg-[#0f0f0f] border border-[#444] rounded px-3 py-2 text-sm text-white">
                        </div>
                        <button onclick="handleLogin()" class="btn-red w-full py-2 rounded font-bold">安全登录</button>
                    </div>
                </div>
                <div id="auth-reg-panel" class="hidden space-y-3">
                    <input type="text" id="reg-user" placeholder="用户名" class="w-full bg-[#0f0f0f] border border-[#444] rounded px-3 py-2 text-white text-sm">
                    <input type="password" id="reg-pass" placeholder="密码" class="w-full bg-[#0f0f0f] border border-[#444] rounded px-3 py-2 text-white text-sm">
                    <input type="email" id="reg-email" placeholder="邮箱" class="w-full bg-[#0f0f0f] border border-[#444] rounded px-3 py-2 text-white text-sm">
                    <select id="reg-question" class="w-full bg-[#0f0f0f] border border-[#444] rounded px-2 py-1.5 text-sm text-gray-300">
                        <option>您母亲的姓名是？</option>
                        <option>您出生的城市是？</option>
                    </select>
                    <input type="text" id="reg-answer" placeholder="密保答案" class="w-full bg-[#0f0f0f] border border-[#444] rounded px-3 py-2 text-white text-sm">
                    <div class="flex items-start gap-2 text-xs text-gray-400">
                        <input type="checkbox" id="agree-law" class="mt-0.5">
                        <label for="agree-law">同意<a href="#" onclick="showRules()" class="text-[#8B0000]">《社区法规》</a></label>
                    </div>
                    <button onclick="handleRegister()" class="btn-metal w-full py-2 rounded text-white font-bold">注册</button>
                </div>
            </div>
            <button onclick="closeAuth()" class="absolute top-4 right-4 text-gray-500 hover:text-white"><i class="fas fa-times"></i></button>
        </div>
    </div>

    <!-- 发帖模态框 -->
    <div id="post-modal" class="hidden fixed inset-0 z-[1000] bg-black/90 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-[#1f1f1f] border border-[#444] rounded-lg w-full max-w-3xl max-h-[90vh] flex flex-col modal-enter">
            <div class="flex items-center justify-between p-4 border-b border-[#444]">
                <h3 class="font-bold text-white" id="post-modal-title">发布新帖</h3>
                <button onclick="closePostModal()" class="text-gray-500 hover:text-white"><i class="fas fa-times"></i></button>
            </div>
            <div class="p-4 space-y-3 overflow-y-auto flex-1">
                <input type="hidden" id="edit-post-id">
                <input type="text" id="post-title" placeholder="标题" class="w-full bg-[#0f0f0f] border border-[#444] rounded px-3 py-2 text-white">
                <textarea id="post-content" rows="10" placeholder="正文..." class="w-full bg-[#0f0f0f] border border-[#444] rounded px-3 py-2 text-white resize-none"></textarea>
            </div>
            <div class="p-4 border-t border-[#444] flex justify-end gap-2">
                <button onclick="closePostModal()" class="btn-metal px-4 py-1.5 rounded text-sm">取消</button>
                <button onclick="submitPost()" class="btn-red px-6 py-1.5 rounded text-sm font-bold">发布</button>
            </div>
        </div>
    </div>

    <script>
        // ================= 数据存储 =================
        const DB = {
            currentUser: null,
            presidentKey: false,
            
            // 商品库
            shopItems: [
                {id: 'frame_gold', name: '金质头像框', type: 'frame', price: 500, icon: '👑', desc: '尊贵金色边框，彰显站长权威（仅装饰）', style: 'avatar-frame-gold', permanent: true},
                {id: 'frame_silver', name: '银质头像框', type: 'frame', price: 300, icon: '⚙️', desc: '工程师专属银色边框', style: 'avatar-frame-silver', permanent: true},
                {id: 'frame_bronze', name: '铜质头像框', type: 'frame', price: 150, icon: '🛤️', desc: '资深车迷铜色边框', style: 'avatar-frame-bronze', permanent: true},
                {id: 'frame_rail', name: '铁路红边框', type: 'frame', price: 100, icon: '🚂', desc: '大秦线经典红色', style: 'avatar-frame-rail', permanent: true},
                {id: 'name_gold', name: '金色ID', type: 'namecolor', price: 200, icon: '🟡', desc: '土豪金用户名显示', style: 'name-gold', permanent: true},
                {id: 'name_red', name: '赤色ID', type: 'namecolor', price: 200, icon: '🔴', desc: '醒目红色用户名', style: 'name-red', permanent: true},
                {id: 'badge_engineer', name: '工程师勋章', type: 'badge', price: 300, icon: '⚙️', desc: '技术大牛标识', badgeIcon: '⚙️', badgeColor: 'bg-gray-700', permanent: true},
                {id: 'badge_photographer', name: '摄影师勋章', type: 'badge', price: 300, icon: '📷', desc: '摄影达人标识', badgeIcon: '📷', badgeColor: 'bg-purple-700', permanent: true},
                {id: 'badge_oldfan', name: '老司机勋章', type: 'badge', price: 500, icon: '🎖️', desc: '资深车迷专属', badgeIcon: '🎖️', badgeColor: 'bg-[#8B0000]', permanent: true},
                {id: 'title_rebirth', name: '称号：转生车迷', type: 'title', price: 1000, icon: '🌟', desc: '尊贵身份象征，显示在用户名旁', permanent: true}
            ],
            
            posts: [
                {id: 1, title: "【公告】社区法规更新通知", content: "各位车迷朋友：\n\n为了维护社区良好的技术交流氛围，现将法规更新如下：\n\n1. 严禁发布涉密铁路信息\n2. 技术讨论请保持友善态度\n3. 摄影作品请标注拍摄地点和安全提示\n\n违反以上规定者，按《信息系统安全保护条例》处理。\n\n山西省晋北畅行交通文化社\n2025年1月31日", author: "system", authorName: "管理员", type: "公告", isSticky: true, createTime: "2025-01-31 10:00", views: 1200, replies: 5, authorAvatar: null, rewards: 0},
                {id: 2, title: "HXD1型机车技术讨论", content: "最近研究了HXD1型电力机车的牵引系统，想和大家分享一下心得：\n\n这款机车采用交直交传动，功率达到9600kW，是目前重载运输的主力机型。\n\n有几个问题想请教：\n1. 再生制动效率在实际运用中如何？\n2. 牵引变流器的冷却系统维护周期是多久？\n\n期待各位同行老师傅指点！", author: "user001", authorName: "铁道迷小李", type: "技术", isSticky: false, createTime: "2025-01-31 14:30", views: 456, replies: 23, authorAvatar: null, rewards: 0}
            ],
            
            users: {
                'user001': { 
                    username: 'user001', 
                    password: '123456', 
                    security: '保密', 
                    role: 'user', 
                    points: 250,
                    avatar: null,
                    inventory: [],
                    equipped: {frame: null, namecolor: null, badges: []}
                },
                'Wunji': { 
                    username: 'Wunji', 
                    password: '1234578wW', 
                    security: '20121126', 
                    role: 'president', 
                    points: Infinity, // 无限积分
                    avatar: null,
                    inventory: ['frame_gold', 'badge_oldfan', 'name_gold'],
                    equipped: {frame: 'frame_gold', namecolor: 'name_gold', badges: ['badge_oldfan']}
                }
            }
        };

        let tempAvatarData = null;
        let currentRewardPostId = null;
        let selectedRewardAmount = 0;
        let expandedPostId = null; // 记录当前展开的帖子ID

        // ================= 初始化 =================
        document.addEventListener('DOMContentLoaded', () => {
            updateTime();
            setInterval(updateTime, 1000);
            renderPosts();
            updateStats();
        });

        function updateTime() {
            const now = new Date();
            document.getElementById('beijing-time').textContent = now.toLocaleString('zh-CN', {hour12: false});
        }

        function updateStats() {
            document.getElementById('stat-posts').textContent = DB.posts.length;
        }

        // ================= 无限积分系统 =================
        
        // 检查是否为会长（无限积分）
        function isPresident() {
            return DB.currentUser && DB.currentUser.role === 'president';
        }

        // 获取显示的积分文本
        function getDisplayPoints(user = DB.currentUser) {
            if (!user) return '0';
            if (user.role === 'president') return '∞';
            return user.points;
        }

        // 检查积分是否足够（会长永远返回true）
        function hasEnoughPoints(amount) {
            if (isPresident()) return true;
            return DB.currentUser && DB.currentUser.points >= amount;
        }

        // 修改积分（会长不扣减，只做记录）
        function modifyPoints(amount, reason = '', targetUser = null) {
            const user = targetUser || DB.currentUser;
            if (!user) return;
            
            const isPres = user.role === 'president';
            const isCurrent = user === DB.currentUser;
            
            // 如果不是会长，或者目标是其他用户（管理操作），则正常修改积分
            if (!isPres || (targetUser && targetUser !== DB.currentUser)) {
                user.points += amount;
                if (user.points < 0) user.points = 0;
            } else if (isPres && isCurrent && amount < 0) {
                // 会长消费，记录但不扣减
                console.log(`[无限积分消费] ${reason || '消费'}: ${Math.abs(amount)}，实际未扣减`);
            }
            
            // 更新UI
            if (isCurrent) {
                updatePointsDisplay();
                
                // 浮动动画（只有实际扣减积分的用户显示）
                if (amount !== 0 && !isPres) {
                    showPointsFloat(amount);
                    if (reason) showToast(`${reason} ${amount > 0 ? '+' : ''}${amount}积分`, amount > 0 ? 'success' : 'info');
                } else if (isPres && amount < 0) {
                    showToast(`${reason} ${Math.abs(amount)}积分（免扣）`, 'info');
                }
            }
        }

        function showPointsFloat(amount) {
            const floatEl = document.createElement('div');
            floatEl.className = 'points-float';
            floatEl.textContent = amount > 0 ? `+${amount}` : `${amount}`;
            floatEl.style.left = '50%';
            floatEl.style.top = '50%';
            document.body.appendChild(floatEl);
            setTimeout(() => floatEl.remove(), 1000);
        }

        // 更新所有积分显示位置
        function updatePointsDisplay() {
            const display = getDisplayPoints();
            const els = ['nav-points', 'sidebar-points', 'shop-points'];
            els.forEach(id => {
                const el = document.getElementById(id);
                if (el) el.textContent = display;
            });
        }

        // ================= 打赏系统 =================

        // 打开打赏模态框
        function openRewardModal(postId) {
            if (!DB.currentUser) {
                showAuth();
                return;
            }
            
            const post = DB.posts.find(p => p.id === postId);
            if (!post) return;
            
            // 不能打赏自己
            if (post.author === DB.currentUser.username) {
                showToast('不能打赏自己的帖子', 'error');
                return;
            }
            
            currentRewardPostId = postId;
            document.getElementById('reward-target-name').textContent = post.authorName;
            document.getElementById('reward-modal').classList.remove('hidden');
            
            // 重置选择
            selectedRewardAmount = 0;
            updateRewardCalculation();
            document.querySelectorAll('.reward-btn').forEach(btn => {
                btn.classList.remove('border-[#DAA520]', 'bg-[#DAA520]/20');
                btn.classList.add('border-[#444]');
            });
            document.getElementById('reward-custom-amount').value = '';
            document.getElementById('reward-submit-btn').disabled = true;
            document.getElementById('reward-submit-btn').classList.add('opacity-50', 'cursor-not-allowed');
        }

        function closeRewardModal() {
            document.getElementById('reward-modal').classList.add('hidden');
            currentRewardPostId = null;
            selectedRewardAmount = 0;
        }

        function selectRewardAmount(amount) {
            selectedRewardAmount = amount;
            document.getElementById('reward-custom-amount').value = '';
            
            // 更新按钮样式
            document.querySelectorAll('.reward-btn').forEach(btn => {
                const btnAmount = parseInt(btn.dataset.amount);
                if (btnAmount === amount) {
                    btn.classList.add('border-[#DAA520]', 'bg-[#DAA520]/20');
                    btn.classList.remove('border-[#444]');
                } else {
                    btn.classList.remove('border-[#DAA520]', 'bg-[#DAA520]/20');
                    btn.classList.add('border-[#444]');
                }
            });
            
            updateRewardCalculation();
            enableRewardBtn();
        }

        // 监听自定义金额输入
        document.addEventListener('DOMContentLoaded', () => {
            const customInput = document.getElementById('reward-custom-amount');
            if (customInput) {
                customInput.addEventListener('input', function(e) {
                    const val = parseInt(e.target.value);
                    if (val >= 10 && val % 10 === 0) {
                        selectedRewardAmount = val;
                        // 清除预设按钮选中状态
                        document.querySelectorAll('.reward-btn').forEach(btn => {
                            btn.classList.remove('border-[#DAA520]', 'bg-[#DAA520]/20');
                            btn.classList.add('border-[#444]');
                        });
                        updateRewardCalculation();
                        enableRewardBtn();
                    } else {
                        selectedRewardAmount = 0;
                        updateRewardCalculation();
                        disableRewardBtn();
                    }
                });
            }
        });

        function updateRewardCalculation() {
            const pay = selectedRewardAmount;
            const get = Math.floor(pay / 10); // 10积分=1积分
            const fee = pay - get;
            
            document.getElementById('reward-pay').textContent = pay + ' 积分';
            document.getElementById('reward-get').textContent = get + ' 积分';
            document.getElementById('reward-fee').textContent = fee + ' 积分';
        }

        function enableRewardBtn() {
            const btn = document.getElementById('reward-submit-btn');
            if (selectedRewardAmount >= 10) {
                btn.disabled = false;
                btn.classList.remove('opacity-50', 'cursor-not-allowed');
            }
        }

        function disableRewardBtn() {
            const btn = document.getElementById('reward-submit-btn');
            btn.disabled = true;
            btn.classList.add('opacity-50', 'cursor-not-allowed');
        }

        function submitReward() {
            if (!currentRewardPostId || selectedRewardAmount < 10) return;
            
            const post = DB.posts.find(p => p.id === currentRewardPostId);
            if (!post) return;
            
            // 检查余额（会长跳过）
            if (!isPresident() && DB.currentUser.points < selectedRewardAmount) {
                showToast('积分不足', 'error');
                return;
            }
            
            const authorData = DB.users[post.author];
            const rewardToAuthor = Math.floor(selectedRewardAmount / 10);
            
            // 扣除打赏者积分（会长不扣）
            modifyPoints(-selectedRewardAmount, '打赏帖子');
            
            // 增加作者积分
            if (authorData) {
                authorData.points += rewardToAuthor;
                // 如果作者是当前登录用户，更新显示
                if (authorData === DB.currentUser) {
                    updatePointsDisplay();
                }
            }
            
            // 增加帖子打赏数
            post.rewards = (post.rewards || 0) + 1;
            
            showToast(`打赏成功！${post.authorName} 获得 ${rewardToAuthor} 积分`, 'success');
            closeRewardModal();
            renderPosts();
        }

        // ================= 商城系统（支持无限积分） =================

        function buyItem(itemId) {
            if (!DB.currentUser) {
                showToast('请先登录', 'error');
                return;
            }
            
            const item = DB.shopItems.find(i => i.id === itemId);
            if (!item) return;
            
            // 检查是否已拥有
            if (DB.currentUser.inventory.includes(itemId)) {
                showToast('您已拥有此物品', 'warning');
                return;
            }
            
            // 检查积分（非会长需要检查）
            if (!isPresident() && DB.currentUser.points < item.price) {
                showToast(`积分不足，需要${item.price}积分`, 'error');
                return;
            }
            
            // 确认购买
            const confirmMsg = isPresident() ? 
                `确认免费购买【${item.name}】？\n\n${item.desc}\n\n（会长无限积分特权）` :
                `确认花费 ${item.price} 积分购买【${item.name}】？\n\n${item.desc}`;
            
            if (!confirm(confirmMsg)) return;
            
            // 扣积分（会长不扣）
            modifyPoints(-item.price, '购买' + item.name);
            
            // 加入背包
            DB.currentUser.inventory.push(itemId);
            
            // 自动装备逻辑
            let equipped = false;
            if (item.type === 'frame' && !DB.currentUser.equipped.frame) {
                DB.currentUser.equipped.frame = itemId;
                equipped = true;
            } else if (item.type === 'namecolor' && !DB.currentUser.equipped.namecolor) {
                DB.currentUser.equipped.namecolor = itemId;
                equipped = true;
            } else if (item.type === 'badge' && DB.currentUser.equipped.badges.length === 0) {
                DB.currentUser.equipped.badges.push(itemId);
                equipped = true;
            }
            
            showToast(equipped ? '购买成功！已自动装备' : '购买成功！请到背包装备', 'success');
            
            renderShop();
            renderInventory();
            renderPosts();
            document.getElementById('user-item-count').textContent = DB.currentUser.inventory.length;
        }

        function toggleEquip(itemId) {
            const item = DB.shopItems.find(i => i.id === itemId);
            if (!item || !DB.currentUser.inventory.includes(itemId)) return;
            
            if (item.type === 'frame') {
                DB.currentUser.equipped.frame = DB.currentUser.equipped.frame === itemId ? null : itemId;
            } else if (item.type === 'namecolor') {
                DB.currentUser.equipped.namecolor = DB.currentUser.equipped.namecolor === itemId ? null : itemId;
            } else if (item.type === 'badge') {
                const idx = DB.currentUser.equipped.badges.indexOf(itemId);
                if (idx > -1) DB.currentUser.equipped.badges.splice(idx, 1);
                else DB.currentUser.equipped.badges.push(itemId);
            }
            
            renderInventory();
            renderInventoryDetail();
            renderPosts();
            showToast('装备已更新', 'success');
        }

        // ================= UI 函数 =================

        function openShop() {
            if (!DB.currentUser) {
                showAuth();
                return;
            }
            document.getElementById('shop-modal').classList.remove('hidden');
            updatePointsDisplay();
            renderShop();
            renderInventory();
        }

        function closeShop() {
            document.getElementById('shop-modal').classList.add('hidden');
        }

        function renderShop() {
            const container = document.getElementById('shop-items');
            container.innerHTML = '';
            
            DB.shopItems.forEach(item => {
                const isOwned = DB.currentUser.inventory.includes(item.id);
                const canAfford = isPresident() || DB.currentUser.points >= item.price;
                
                const div = document.createElement('div');
                div.className = `shop-item rounded-lg p-4 flex flex-col ${isOwned ? 'opacity-60' : ''}`;
                
                // 会长显示"免费"而不是价格
                const priceDisplay = isPresident() ? 
                    '<span class="text-[#DAA520] font-bold text-xs">[会长免费]</span>' :
                    `<div class="flex items-center gap-1 text-[#DAA520] font-bold"><i class="fas fa-coins text-xs"></i><span>${item.price}</span></div>`;
                
                div.innerHTML = `
                    <div class="text-3xl mb-2 text-center">${item.icon}</div>
                    <h4 class="font-bold text-white text-sm mb-1 text-center">${item.name}</h4>
                    <p class="text-xs text-gray-500 mb-3 text-center h-8 overflow-hidden">${item.desc}</p>
                    <div class="mt-auto flex items-center justify-between">
                        ${priceDisplay}
                        <button onclick="${isOwned ? '' : `buyItem('${item.id}')`}" 
                                class="px-3 py-1.5 rounded text-xs font-bold ${isOwned ? 'bg-gray-700 text-gray-400 cursor-not-allowed' : canAfford ? 'btn-gold' : 'bg-gray-700 text-gray-400 cursor-not-allowed'}"
                                ${isOwned || !canAfford ? 'disabled' : ''}>
                            ${isOwned ? '已拥有' : canAfford ? '购买' : '积分不足'}
                        </button>
                    </div>
                `;
                container.appendChild(div);
            });
        }

        function renderInventory() {
            const list = document.getElementById('inventory-list');
            if (DB.currentUser.inventory.length === 0) {
                list.innerHTML = '<p class="text-xs text-gray-500 text-center py-4">暂无装饰品</p>';
                return;
            }
            
            list.innerHTML = DB.currentUser.inventory.map(itemId => {
                const item = DB.shopItems.find(i => i.id === itemId);
                if (!item) return '';
                
                let isEquipped = false;
                if (item.type === 'frame') isEquipped = DB.currentUser.equipped.frame === itemId;
                else if (item.type === 'namecolor') isEquipped = DB.currentUser.equipped.namecolor === itemId;
                else if (item.type === 'badge') isEquipped = DB.currentUser.equipped.badges.includes(itemId);
                
                return `
                    <div class="inventory-item ${isEquipped ? 'equipped' : ''} p-2 rounded flex items-center gap-2 cursor-pointer" onclick="toggleEquip('${item.id}')">
                        <span class="text-lg">${item.icon}</span>
                        <div class="flex-1 min-w-0">
                            <div class="text-xs text-white truncate">${item.name}</div>
                            <div class="text-[10px] text-gray-500">${isEquipped ? '已装备' : '点击装备'}</div>
                        </div>
                    </div>
                `;
            }).join('');
        }

        function openInventory() {
            if (!DB.currentUser) {
                showAuth();
                return;
            }
            document.getElementById('inventory-modal').classList.remove('hidden');
            renderInventoryDetail();
            updatePreview();
        }

        function renderInventoryDetail() {
            const detailList = document.getElementById('inventory-detail-list');
            if (DB.currentUser.inventory.length === 0) {
                detailList.innerHTML = '<div class="col-span-3 text-center text-gray-500 py-8">背包空空如也，快去商城兑换吧！</div>';
            } else {
                detailList.innerHTML = DB.currentUser.inventory.map(itemId => {
                    const item = DB.shopItems.find(i => i.id === itemId);
                    if (!item) return '';
                    
                    let isEquipped = false;
                    if (item.type === 'frame') isEquipped = DB.currentUser.equipped.frame === itemId;
                    else if (item.type === 'namecolor') isEquipped = DB.currentUser.equipped.namecolor === itemId;
                    else if (item.type === 'badge') isEquipped = DB.currentUser.equipped.badges.includes(itemId);
                    
                    return `
                        <div class="bg-[#1a1a1a] border ${isEquipped ? 'border-[#DAA520] bg-[#DAA520]/10' : 'border-[#333]'} rounded-lg p-4 cursor-pointer hover:border-[#DAA520]/50 transition-colors" onclick="toggleEquip('${item.id}')">
                            <div class="text-3xl text-center mb-2">${item.icon}</div>
                            <div class="text-sm font-bold text-white text-center mb-1">${item.name}</div>
                            <div class="text-xs text-gray-500 text-center mb-2">${item.desc}</div>
                            <div class="text-center">
                                <span class="text-xs px-2 py-1 rounded ${isEquipped ? 'bg-[#DAA520] text-black' : 'bg-[#333] text-gray-400'}">
                                    ${isEquipped ? '已装备' : '未装备'}
                                </span>
                            </div>
                        </div>
                    `;
                }).join('');
            }
            document.getElementById('user-item-count').textContent = DB.currentUser.inventory.length;
        }

        function updatePreview() {
            if (!DB.currentUser) return;
            
            const avatar = DB.currentUser.avatar || `https://api.dicebear.com/7.x/avataaars/svg?seed=${DB.currentUser.username}`;
            document.getElementById('preview-avatar').src = avatar;
            
            const frameDiv = document.getElementById('preview-frame');
            frameDiv.className = 'absolute inset-0 rounded-full pointer-events-none';
            if (DB.currentUser.equipped.frame) {
                const frameItem = DB.shopItems.find(i => i.id === DB.currentUser.equipped.frame);
                if (frameItem) frameDiv.classList.add(frameItem.style);
            }
            
            const nameDiv = document.getElementById('preview-username');
            nameDiv.textContent = DB.currentUser.username;
            nameDiv.className = 'font-bold';
            if (DB.currentUser.equipped.namecolor) {
                const colorItem = DB.shopItems.find(i => i.id === DB.currentUser.equipped.namecolor);
                if (colorItem) nameDiv.classList.add(colorItem.style);
            } else {
                nameDiv.classList.add('text-white');
            }
            
            const badgesDiv = document.getElementById('preview-badges');
            badgesDiv.innerHTML = DB.currentUser.equipped.badges.map(badgeId => {
                const badge = DB.shopItems.find(i => i.id === badgeId);
                return `<div class="badge ${badge.badgeColor} text-white" data-title="${badge.name}">${badge.badgeIcon}</div>`;
            }).join('');
        }

        function closeInventory() {
            document.getElementById('inventory-modal').classList.add('hidden');
        }

        // ================= 帖子系统（已添加正文查看功能） =================

        // 切换帖子展开/收起
        function togglePostContent(postId) {
            const contentDiv = document.getElementById(`post-content-${postId}`);
            const rowDiv = document.getElementById(`post-row-${postId}`);
            
            if (expandedPostId === postId) {
                // 收起
                contentDiv.classList.remove('expanded');
                rowDiv.classList.remove('expanded');
                expandedPostId = null;
            } else {
                // 收起其他已展开的帖子
                if (expandedPostId) {
                    const prevContent = document.getElementById(`post-content-${expandedPostId}`);
                    const prevRow = document.getElementById(`post-row-${expandedPostId}`);
                    if (prevContent) prevContent.classList.remove('expanded');
                    if (prevRow) prevRow.classList.remove('expanded');
                }
                
                // 展开当前帖子
                contentDiv.classList.add('expanded');
                rowDiv.classList.add('expanded');
                expandedPostId = postId;
                
                // 增加浏览量
                const post = DB.posts.find(p => p.id === postId);
                if (post && !post.viewed) {
                    post.views++;
                    post.viewed = true; // 标记已浏览，避免重复计数
                    renderPosts();
                }
            }
        }

        function renderPosts() {
            const stickyList = document.getElementById('sticky-list');
            const normalList = document.getElementById('thread-list');
            stickyList.innerHTML = '';
            normalList.innerHTML = '';
            
            DB.posts.forEach(post => {
                const isAuthor = DB.currentUser && DB.currentUser.username === post.author;
                const isPresident = DB.currentUser && DB.currentUser.role === 'president';
                const canEdit = isAuthor || isPresident;
                const canDelete = isAuthor || isPresident;
                const isExpanded = expandedPostId === post.id;
                
                const authorData = DB.users[post.author];
                let nameClass = 'text-gray-400';
                let frameClass = '';
                let badgesHtml = '';
                
                if (authorData) {
                    if (authorData.equipped.namecolor) {
                        const colorItem = DB.shopItems.find(i => i.id === authorData.equipped.namecolor);
                        if (colorItem) nameClass = colorItem.style;
                    }
                    if (authorData.equipped.frame) {
                        const frameItem = DB.shopItems.find(i => i.id === authorData.equipped.frame);
                        if (frameItem) frameClass = frameItem.style;
                    }
                    if (authorData.equipped.badges && authorData.equipped.badges.length > 0) {
                        badgesHtml = authorData.equipped.badges.map(bid => {
                            const badge = DB.shopItems.find(i => i.id === bid);
                            return `<div class="badge ${badge.badgeColor} text-white" data-title="${badge.name}">${badge.badgeIcon}</div>`;
                        }).join('');
                    }
                }
                
                let actions = '';
                if (canEdit || canDelete) {
                    actions = `<div class="flex gap-2 ${isPresident ? 'president-only' : 'author-only'}">`;
                    if (canEdit) actions += `<button onclick="event.stopPropagation(); editPost(${post.id})" class="text-xs px-2 py-1 bg-[#4169E1] rounded text-white">${isPresident && !isAuthor ? '修改' : '编辑'}</button>`;
                    if (canDelete) actions += `<button onclick="event.stopPropagation(); deletePost(${post.id})" class="text-xs px-2 py-1 ${isPresident && !isAuthor ? 'bg-red-600' : 'bg-[#8B0000]'} rounded text-white">${isPresident && !isAuthor ? '强制删除' : '删除'}</button>`;
                    if (isPresident && !post.isSticky) actions += `<button onclick="event.stopPropagation(); stickyPost(${post.id})" class="text-xs px-2 py-1 bg-[#DAA520] rounded text-black font-bold">置顶</button>`;
                    else if (isPresident && post.isSticky) actions += `<button onclick="event.stopPropagation(); unstickyPost(${post.id})" class="text-xs px-2 py-1 bg-[#333] rounded text-white">取消置顶</button>`;
                    actions += '</div>';
                }
                
                // 打赏按钮（非作者可见）
                let rewardBtn = '';
                if (DB.currentUser && !isAuthor) {
                    const rewardCount = post.rewards || 0;
                    rewardBtn = `
                        <button onclick="event.stopPropagation(); openRewardModal(${post.id})" class="flex items-center gap-1 text-xs text-[#DAA520] hover:text-[#FFD700] bg-[#DAA520]/10 hover:bg-[#DAA520]/20 px-2 py-1 rounded transition-colors ml-2" title="打赏">
                            <i class="fas fa-gift"></i>
                            <span>${rewardCount > 0 ? rewardCount : '打赏'}</span>
                        </button>
                    `;
                } else if (!DB.currentUser) {
                    rewardBtn = `
                        <button onclick="event.stopPropagation(); showAuth()" class="flex items-center gap-1 text-xs text-gray-500 hover:text-[#DAA520] bg-[#333] hover:bg-[#444] px-2 py-1 rounded transition-colors ml-2">
                            <i class="fas fa-gift"></i>
                            <span>登录后打赏</span>
                        </button>
                    `;
                } else {
                    // 作者看到自己的帖子显示打赏数但不可点击
                    const rewardCount = post.rewards || 0;
                    if (rewardCount > 0) {
                        rewardBtn = `<span class="flex items-center gap-1 text-xs text-[#DAA520] px-2 py-1 ml-2"><i class="fas fa-gift"></i>${rewardCount}</span>`;
                    }
                }
                
                const row = document.createElement('div');
                row.className = `forum-row p-4 ${post.isSticky ? 'sticky-top' : ''} ${isExpanded ? 'expanded' : ''} cursor-pointer`;
                row.id = `post-row-${post.id}`;
                row.dataset.threadId = post.id;
                row.dataset.isAuthor = isAuthor;
                row.onclick = () => togglePostContent(post.id);
                
                const avatarUrl = post.authorAvatar || (authorData && authorData.avatar) || `https://api.dicebear.com/7.x/avataaars/svg?seed=${post.author}`;
                
                row.innerHTML = `
                    <div class="flex justify-between items-start gap-4">
                        <div class="flex-1 min-w-0">
                            <div class="flex items-center gap-2 mb-1">
                                ${post.isSticky ? '<i class="fas fa-thumbtack text-[#DAA520] text-xs"></i>' : ''}
                                <span class="text-xs border border-current px-1 rounded ${post.type === '技术' ? 'text-blue-400' : post.type === '公告' ? 'text-[#DAA520]' : 'text-gray-400'}">${post.type}</span>
                                <h3 class="font-medium truncate hover:text-[#DAA520] text-white flex items-center gap-2">
                                    ${post.title}
                                    <i class="fas fa-chevron-down text-xs text-gray-500 expand-indicator transition-transform ${isExpanded ? 'rotate-180' : ''}"></i>
                                </h3>
                            </div>
                            <div class="flex items-center gap-3 text-xs text-gray-500 flex-wrap">
                                <div class="relative">
                                    <img src="${avatarUrl}" class="w-5 h-5 rounded-full object-cover bg-[#333] ${frameClass}">
                                </div>
                                <span class="${nameClass} font-bold">${post.authorName}</span>
                                ${badgesHtml}
                                <span>${post.createTime}</span>
                                <span><i class="far fa-eye"></i> ${post.views}</span>
                                <span><i class="far fa-comment"></i> ${post.replies}</span>
                                ${rewardBtn}
                            </div>
                            
                            <!-- 帖子正文内容区域 -->
                            <div id="post-content-${post.id}" class="post-content ${isExpanded ? 'expanded' : ''}" onclick="event.stopPropagation()">
                                <div class="post-content-text bg-[#0f0f0f] p-4 rounded border border-[#333] mt-2 relative">
                                    ${post.content}
                                    <div class="absolute top-2 right-2 text-xs text-gray-600">
                                        <i class="fas fa-clock mr-1"></i>${post.createTime}
                                    </div>
                                </div>
                                <div class="flex justify-between items-center mt-3">
                                    <div class="text-xs text-gray-500">
                                        点击标题可收起内容
                                    </div>
                                    <div class="flex gap-2">
                                        ${isAuthor ? '<span class="text-xs text-[#8B0000] border border-[#8B0000] px-2 py-1 rounded">我的帖子</span>' : ''}
                                        ${post.isSticky ? '<span class="text-xs text-[#DAA520] border border-[#DAA520] px-2 py-1 rounded">置顶</span>' : ''}
                                    </div>
                                </div>
                            </div>
                        </div>
                        ${actions}
                    </div>
                `;
                
                if (post.isSticky) stickyList.appendChild(row);
                else normalList.appendChild(row);
            });
        }

        function submitPost() {
            const title = document.getElementById('post-title').value.trim();
            const content = document.getElementById('post-content').value.trim();
            const editId = document.getElementById('edit-post-id').value;
            
            if (!title || !content) {
                showToast('标题和内容不能为空', 'error');
                return;
            }
            
            if (editId) {
                const post = DB.posts.find(p => p.id == editId);
                if (post && (post.author === DB.currentUser.username || DB.currentUser.role === 'president')) {
                    post.title = title;
                    post.content = content;
                    showToast('修改成功', 'success');
                }
            } else {
                const newPost = {
                    id: Date.now(),
                    title: title,
                    content: content,
                    author: DB.currentUser.username,
                    authorName: DB.currentUser.username,
                    type: '讨论',
                    isSticky: false,
                    createTime: new Date().toLocaleString('zh-CN', {hour12: false}),
                    views: 0,
                    replies: 0,
                    authorAvatar: DB.currentUser.avatar,
                    rewards: 0
                };
                DB.posts.unshift(newPost);
                
                modifyPoints(10, '发布帖子');
                showToast('发布成功，获得10积分！', 'success');
            }
            
            closePostModal();
            renderPosts();
            updateStats();
        }

        // ================= 原有系统 =================

        let secretClickCount = 0;
        let lastClickTime = 0;
        function handleSecretTrigger() {
            const now = Date.now();
            if (now - lastClickTime > 2000) secretClickCount = 0;
            lastClickTime = now;
            secretClickCount++;
            if (secretClickCount === 5) activatePresidentLogin();
        }
        
        let shiftPCount = 0;
        let shiftPTimer = null;
        document.addEventListener('keydown', (e) => {
            if (e.shiftKey && e.key === 'P') {
                shiftPCount++;
                if (!shiftPTimer) shiftPTimer = setTimeout(() => { shiftPCount = 0; shiftPTimer = null; }, 3000);
                if (shiftPCount === 3) { activatePresidentLogin(); shiftPCount = 0; clearTimeout(shiftPTimer); shiftPTimer = null; }
            }
        });

        function activatePresidentLogin() {
            DB.presidentKey = true;
            document.getElementById('president-question').classList.remove('hidden');
            document.getElementById('login-question').value = 'president';
            showToast('⚠️ 检测到管理员密钥', 'warning');
        }

        function handleLogin() {
            const user = document.getElementById('login-user').value;
            const pass = document.getElementById('login-pass').value;
            const security = document.getElementById('login-security').value;
            const question = document.getElementById('login-question').value;
            
            if (!user || !pass || !security) { showToast('请填写完整信息', 'error'); return; }
            
            if (question === 'president' && DB.presidentKey) {
                if (user === 'Wunji' && pass === '1234578wW' && security === '20121126') {
                    loginSuccess(DB.users['Wunji']);
                    showToast('👑 管理员登录成功（无限积分模式）', 'success');
                    return;
                } else { showToast('管理员验证失败', 'error'); return; }
            }
            
            const userData = DB.users[user];
            if (userData && userData.password === pass && userData.security === security) {
                loginSuccess(userData);
                showToast('登录成功', 'success');
            } else { showToast('账号、密码或密保错误', 'error'); }
        }

        function loginSuccess(userData) {
            DB.currentUser = userData;
            document.getElementById('auth-modal').classList.add('hidden');
            document.getElementById('guest-state').classList.add('hidden');
            document.getElementById('user-state').classList.remove('hidden');
            document.getElementById('nav-username').textContent = userData.username;
            document.getElementById('sidebar-profile').classList.remove('hidden');
            document.getElementById('sidebar-username').textContent = userData.username;
            document.getElementById('sidebar-role').textContent = userData.role === 'president' ? '管理员' : '注册用户';
            updatePointsDisplay();
            document.getElementById('user-post-count').textContent = DB.posts.filter(p => p.author === userData.username).length;
            document.getElementById('user-item-count').textContent = userData.inventory ? userData.inventory.length : 0;
            
            updateAvatarDisplay();
            
            if (userData.role === 'president') {
                document.body.classList.add('president-mode');
                // 会长登录提示
                setTimeout(() => {
                    showToast('💰 无限积分特权已激活：任意消费不扣积分', 'success');
                }, 1000);
            }
            renderPosts();
        }

        function logout() {
            DB.currentUser = null;
            DB.presidentKey = false;
            document.body.classList.remove('president-mode');
            expandedPostId = null; // 重置展开状态
            document.getElementById('guest-state').classList.remove('hidden');
            document.getElementById('user-state').classList.add('hidden');
            document.getElementById('sidebar-profile').classList.add('hidden');
            renderPosts();
        }

        function showAuth() { 
            document.getElementById('auth-modal').classList.remove('hidden'); 
        }
        function closeAuth() { 
            document.getElementById('auth-modal').classList.add('hidden'); 
        }
        function switchAuth(type) {
            document.getElementById('auth-login-panel').classList.toggle('hidden', type !== 'login');
            document.getElementById('auth-reg-panel').classList.toggle('hidden', type !== 'register');
            document.getElementById('auth-tab-login').className = `flex-1 py-3 text-center font-bold ${type === 'login' ? 'bg-[#8B0000] text-white' : 'text-gray-400 hover:bg-[#2a2a2a]'}`;
            document.getElementById('auth-tab-reg').className = `flex-1 py-3 text-center font-bold ${type === 'register' ? 'bg-[#8B0000] text-white' : 'text-gray-400 hover:bg-[#2a2a2a]'}`;
        }
        function openPostModal() { 
            if (!DB.currentUser) { showAuth(); return; } 
            document.getElementById('post-modal').classList.remove('hidden'); 
            document.getElementById('post-title').value = '';
            document.getElementById('post-content').value = '';
            document.getElementById('edit-post-id').value = '';
            document.getElementById('post-modal-title').textContent = '发布新帖';
        }
        function closePostModal() { 
            document.getElementById('post-modal').classList.add('hidden'); 
        }
        function handleRegister() { 
            showToast('注册功能已关闭（演示模式）', 'error'); 
        }
        function showRules() { 
            alert('社区法规：严禁传播涉密信息，违者依法处理。\n\n打赏规则：打赏10积分，作者获得1积分（10%转化率，类似B站投币机制）'); 
        }
        function editPost(id) { 
            const post = DB.posts.find(p => p.id === id);
            if (post) {
                document.getElementById('post-title').value = post.title;
                document.getElementById('post-content').value = post.content;
                document.getElementById('edit-post-id').value = id;
                document.getElementById('post-modal-title').textContent = '编辑帖子';
                document.getElementById('post-modal').classList.remove('hidden');
            }
        }
        function deletePost(id) { 
            if (confirm('确定删除？')) {
                const post = DB.posts.find(p => p.id === id);
                const isAuthor = post && DB.currentUser && post.author === DB.currentUser.username;
                
                // 如果当前展开的帖子被删除，重置展开状态
                if (expandedPostId === id) {
                    expandedPostId = null;
                }
                
                DB.posts = DB.posts.filter(p => p.id !== id);
                renderPosts();
                updateStats();
                
                // 只有作者删除自己的帖子才扣分，会长删除不扣
                if (isAuthor && !isPresident()) {
                    modifyPoints(-5, '删除帖子');
                }
            }
        }
        function stickyPost(id) { 
            const p = DB.posts.find(p => p.id === id); 
            if (p) { 
                p.isSticky = true; 
                renderPosts(); 
            } 
        }
        function unstickyPost(id) { 
            const p = DB.posts.find(p => p.id === id); 
            if (p) { 
                p.isSticky = false; 
                renderPosts(); 
            } 
        }

        // 头像系统
        function openAvatarModal() { 
            if (!DB.currentUser) return; 
            document.getElementById('avatar-modal').classList.remove('hidden'); 
            document.getElementById('avatar-current-preview').src = DB.currentUser.avatar || `https://api.dicebear.com/7.x/avataaars/svg?seed=${DB.currentUser.username}`;
            tempAvatarData = null;
            document.getElementById('avatar-new-preview-container').classList.add('hidden');
            document.getElementById('avatar-save-btn').disabled = true;
            document.getElementById('avatar-save-btn').classList.add('opacity-50');
        }
        function closeAvatarModal() { 
            document.getElementById('avatar-modal').classList.add('hidden'); 
        }
        function handleAvatarSelect(e) {
            const file = e.target.files[0];
            if (!file) return;
            if (file.size > 2 * 1024 * 1024) { 
                showToast('图片不能超过2MB', 'error'); 
                return; 
            }
            const reader = new FileReader();
            reader.onload = function(evt) {
                tempAvatarData = evt.target.result;
                document.getElementById('avatar-new-preview').src = tempAvatarData;
                document.getElementById('avatar-new-preview-container').classList.remove('hidden');
                document.getElementById('avatar-save-btn').disabled = false;
                document.getElementById('avatar-save-btn').classList.remove('opacity-50');
            };
            reader.readAsDataURL(file);
        }
        function saveAvatar() {
            if (!tempAvatarData || !DB.currentUser) return;
            DB.currentUser.avatar = tempAvatarData;
            updateAvatarDisplay();
            showToast('头像更新成功', 'success');
            closeAvatarModal();
            renderPosts();
        }
        function updateAvatarDisplay() {
            if (!DB.currentUser) return;
            const url = DB.currentUser.avatar || `https://api.dicebear.com/7.x/avataaars/svg?seed=${DB.currentUser.username}`;
            document.getElementById('user-avatar').src = url;
            document.getElementById('sidebar-avatar').src = url;
        }
        function managePoints() {
            if (!isPresident()) return;
            // 简单管理功能：给指定用户加减积分
            const target = prompt('请输入目标用户名：');
            if (!target) return;
            const user = DB.users[target];
            if (!user) {
                showToast('用户不存在', 'error');
                return;
            }
            const amount = parseInt(prompt(`当前用户 ${target} 积分：${getDisplayPoints(user)}\n请输入要调整的积分数量（负数扣除）：`));
            if (isNaN(amount)) return;
            
            user.points += amount;
            showToast(`已调整 ${target} 积分 ${amount > 0 ? '+' : ''}${amount}`, 'success');
            console.log(`[ADMIN] ${DB.currentUser.username} 调整 ${target} 积分 ${amount}`);
            
            // 如果调整的是当前用户，更新显示
            if (user === DB.currentUser) {
                updatePointsDisplay();
            }
        }
        function viewAuditLog() { 
            alert('审计日志：仅会长可见\n\n最近操作：\n1. 系统初始化完成\n2. 积分系统加载完成\n3. 无限积分特权已激活'); 
        }

        function showToast(msg, type = 'info') {
            const toast = document.createElement('div');
            const colors = { success: 'bg-green-600', error: 'bg-red-600', warning: 'bg-yellow-600', info: 'bg-blue-600' };
            toast.className = `fixed top-20 right-4 ${colors[type] || colors.info} text-white px-4 py-2 rounded shadow-lg z-[9999] animate-bounce`;
            toast.textContent = msg;
            document.body.appendChild(toast);
            setTimeout(() => toast.remove(), 3000);
        }
    </script>
</body>
</html>
