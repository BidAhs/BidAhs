```js
export default class MyProfile {
  constructor() { }

  /**
   * @returns {string} Gender
   */
  get gender() {
    return "male";
  }

  /**
   * @returns {Array<string>}
   */
  get skillset() {
    return [
      'NodeJS','Python','HTML/CSS','PHP'
    ];
  }

  /**
   * @returns {Object}
   */
  get socials() {
    return {
      "steam"  : "https://steamcommunity.com/id/bidahs",
      "codewars" : "https://www.codewars.com/users/BidAhs",
    }
  }
}
```
