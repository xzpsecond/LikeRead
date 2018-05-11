# LikeRead

{
  "pages": [
    "pages/component/bookstack/bookstack",
    "pages/component/search/search",
    "pages/component/ranking/ranking",
    "pages/component/classify/classify",
    "pages/component/more/more",
    "pages/component/ranking/rankingtwo",
    "pages/component/bookdetail/bookdetail",
    "pages/component/readbook/readbook",
    "pages/component/comment/commentlist",
    "pages/component/comment/commentdetail",
    "pages/component/classify/classifylist",
    "pages/component/search/searchlist"
  ],
  "window": {
    "backgroundTextStyle": "light",
    "navigationBarBackgroundColor": "#1A8CFF",
    "navigationBarTitleText": "爱读小书",
    "navigationBarTextStyle": "white"
  },
  "tabBar": {
    "color": "#7A7E83",
    "selectedColor": "#1A8CFF",
    "borderStyle": "white",
    "backgroundColor": "#F6F8F9",
    "list": [
      {
        "pagePath": "pages/component/bookstack/bookstack",
        "iconPath": "images/tab_bookstack_normal.png",
        "selectedIconPath": "images/tab_bookstack_selected.png",
        "text": "书架"
      },
      {
        "pagePath": "pages/component/search/search",
        "iconPath": "images/tab_search_normal.png",
        "selectedIconPath": "images/tab_search_selected.png",
        "text": "搜索"
      },
      {
        "pagePath": "pages/component/ranking/ranking",
        "iconPath": "images/tab_ranking_normal.png",
        "selectedIconPath": "images/tab_ranking_selected.png",
        "text": "排行"
      },
      {
        "pagePath": "pages/component/classify/classify",
        "iconPath": "images/tab_classify_normal.png",
        "selectedIconPath": "images/tab_classify_selected.png",
        "text": "分类"
      },
      {
        "pagePath": "pages/component/more/more",
        "iconPath": "images/tab_more_normal.png",
        "selectedIconPath": "images/tab_more_selected.png",
        "text": "更多"
      }
    ],
    "position": "bottom"
  },
  "networkTimeout": {
    "request": 30000,
    "connectSocket": 30000,
    "uploadFile": 30000,
    "downloadFile": 30000
  },
  "debug": false
}