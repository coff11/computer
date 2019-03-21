<template>
  <div style="width: 1030px; margin: 0 auto;">
    <div class="condition" style="margin: 10px 0; text-align: center; font-size: 24px; color: #909399;">
      <i class="el-icon-document"></i> 条件
    </div>
    <el-card class="box-card">
      <el-input style="width: 240px;" v-model="inputA1" placeholder="请输入最小值（-50代表x<50）"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputB1" placeholder="积分1"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputC1" placeholder="积分5"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputD1" placeholder="积分9"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputE1" placeholder="积分19"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputF1" placeholder="积分99"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputG1" placeholder="奖券"></el-input>
    </el-card>
    <el-card class="box-card">
      <el-input style="width: 240px;" v-model="inputA2" placeholder="请输入区间，如：-50,-20"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputB2" placeholder="积分1"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputC2" placeholder="积分5"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputD2" placeholder="积分9"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputE2" placeholder="积分19"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputF2" placeholder="积分99"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputG2" placeholder="奖券"></el-input>
    </el-card>
    <el-card class="box-card">
      <el-input style="width: 240px;" v-model="inputA3" placeholder="请输入区间"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputB3" placeholder="积分1"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputC3" placeholder="积分5"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputD3" placeholder="积分9"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputE3" placeholder="积分19"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputF3" placeholder="积分99"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputG3" placeholder="奖券"></el-input>
    </el-card>
    <el-card class="box-card">
      <el-input style="width: 240px;" v-model="inputA4" placeholder="请输入区间"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputB4" placeholder="积分1"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputC4" placeholder="积分5"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputD4" placeholder="积分9"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputE4" placeholder="积分19"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputF4" placeholder="积分99"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputG4" placeholder="奖券"></el-input>
    </el-card>
    <el-card class="box-card">
      <el-input style="width: 240px;" v-model="inputA5" placeholder="请输入区间"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputB5" placeholder="积分1"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputC5" placeholder="积分5"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputD5" placeholder="积分9"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputE5" placeholder="积分19"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputF5" placeholder="积分99"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputG5" placeholder="奖券"></el-input>
    </el-card>
    <el-card class="box-card">
      <el-input style="width: 240px;" v-model="inputA6" placeholder="请输入区间"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputB6" placeholder="积分1"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputC6" placeholder="积分5"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputD6" placeholder="积分9"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputE6" placeholder="积分19"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputF6" placeholder="积分99"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputG6" placeholder="奖券"></el-input>
    </el-card>
    <el-card class="box-card">
      <el-input style="width: 240px;" v-model="inputA7" placeholder="请输入区间"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputB7" placeholder="积分1"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputC7" placeholder="积分5"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputD7" placeholder="积分9"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputE7" placeholder="积分19"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputF7" placeholder="积分99"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputG7" placeholder="奖券"></el-input>
    </el-card>
    <el-card class="box-card">
      <el-input style="width: 240px;" v-model="inputA8" placeholder="请输入区间"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputB8" placeholder="积分1"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputC8" placeholder="积分5"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputD8" placeholder="积分9"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputE8" placeholder="积分19"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputF8" placeholder="积分99"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputG8" placeholder="奖券"></el-input>
    </el-card>
    <el-card class="box-card">
      <el-input style="width: 240px;" v-model="inputA9" placeholder="请输入区间"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputB9" placeholder="积分1"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputC9" placeholder="积分5"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputD9" placeholder="积分9"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputE9" placeholder="积分19"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputF9" placeholder="积分99"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputG9" placeholder="奖券"></el-input>
    </el-card>
    <el-card class="box-card">
      <el-input style="width: 240px;" v-model="inputA10" placeholder="请输入最大值（50代表x>50）"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputB10" placeholder="积分1"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputC10" placeholder="积分5"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputD10" placeholder="积分9"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputE10" placeholder="积分19"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputF10" placeholder="积分99"></el-input>
      <el-input style="width: 100px; margin: 0 10px;" v-model="inputG10" placeholder="奖券"></el-input>
    </el-card>
    <div class="condition" style="margin: 10px 0; text-align: center; font-size: 24px; color: #909399;">
      <i class="el-icon-setting"></i> 配置
    </div>
    <el-card class="box-card">
      <el-input style="width: 240px;" v-model="inputQ1" placeholder="抽奖次数"></el-input>
      <el-input style="width: 240px; margin: 0 10px;" v-model="inputQ2" placeholder="模拟用户数"></el-input>
      <el-input style="width: 240px; margin: 0 10px;" v-model="inputQ3" placeholder="概率区间划分标准"></el-input>
    </el-card>
    <div style="width: 240px; margin: 30px auto;">
      <el-button type="danger" style="width: 240px;" @click="handleCompute">计算</el-button>
    </div>
    <el-table
      :data="tableData"
      style="width: 360px;">
      <el-table-column
        prop="count"
        label="抽奖次数"
        width="180">
      </el-table-column>
      <el-table-column
        prop="end"
        label="最终积分"
        width="180">
      </el-table-column>
    </el-table>
    <el-table
      :data="tableData2"
      style="width: 100%; margin: 100px 0;">
      <el-table-column
        prop="count"
        label="抽奖次数"
        width="180">
      </el-table-column>
      <el-table-column
        prop="people"
        label="模拟用户数"
        width="180">
      </el-table-column>
      <el-table-column
        prop="max"
        label="最大值"
        width="180">
      </el-table-column>
      <el-table-column
        prop="min"
        label="最小值"
        width="180">
      </el-table-column>
      <el-table-column
        prop="average"
        label="平均值"
        width="180">
      </el-table-column>
    </el-table>
  </div>
</template>

<script>
export default {
  data () {
    return {
      tableData: [],
      tableData2: [],
      mainNumb: 0,
      nums: [0],
      lists: [],
      inputQ1: '',
      inputQ2: '',
      inputQ3: '',
      inputA1: '',
      inputA2: '',
      inputA3: '',
      inputA4: '',
      inputA5: '',
      inputA6: '',
      inputA7: '',
      inputA8: '',
      inputA9: '',
      inputA10: '',
      inputB1: '',
      inputB2: '',
      inputB3: '',
      inputB4: '',
      inputB5: '',
      inputB6: '',
      inputB7: '',
      inputB8: '',
      inputB9: '',
      inputB10: '',
      inputC1: '',
      inputC2: '',
      inputC3: '',
      inputC4: '',
      inputC5: '',
      inputC6: '',
      inputC7: '',
      inputC8: '',
      inputC9: '',
      inputC10: '',
      inputD1: '',
      inputD2: '',
      inputD3: '',
      inputD4: '',
      inputD5: '',
      inputD6: '',
      inputD7: '',
      inputD8: '',
      inputD9: '',
      inputD10: '',
      inputE1: '',
      inputE2: '',
      inputE3: '',
      inputE4: '',
      inputE5: '',
      inputE6: '',
      inputE7: '',
      inputE8: '',
      inputE9: '',
      inputE10: '',
      inputF1: '',
      inputF2: '',
      inputF3: '',
      inputF4: '',
      inputF5: '',
      inputF6: '',
      inputF7: '',
      inputF8: '',
      inputF9: '',
      inputF10: '',
      inputG1: '',
      inputG2: '',
      inputG3: '',
      inputG4: '',
      inputG5: '',
      inputG6: '',
      inputG7: '',
      inputG8: '',
      inputG9: '',
      inputG10: ''
    }
  },
  methods: {
    handleCompute () {
      let q1 = this.inputQ1 || 100
      let q2 = this.inputQ2 || 1
      // let q3 = this.inputQ3
      try {
        for (let j = 0; j < q2; j++) {
          for (let i = 0; i < q1; i++) {
            this.play()
          }
          this.tableData = [
            {
              count: q1,
              end: this.mainNumb
            }
          ]
          this.lists.push(this.mainNumb)
          this.mainNumb = 0
        }
        let newArr = this.lists.sort((a, b) => {
          return parseInt(a) - parseInt(b)
        })
        let average = newArr.reduce((acc, val) => {
          return acc + val
        }, 0) / newArr.length
        this.tableData2 = [
          {
            count: q1,
            people: q2,
            max: newArr[newArr.length - 1],
            min: newArr[0],
            average: average
          }
        ]
      } catch (e) {
        console.log(e)
      }
      // console.log(this.handleLottery(['3', '5', '35', '55', '2', '0']))
      // console.log(this.getResult(['3', '5', '35', '55', '2', '0']))
    },
    play () {
      // 真正的分数是
      this.mainNumb = this.mainNumb - 9
      console.log('开始，扣除9积分，当前积分为', this.mainNumb)
      // 找这个数在哪个区间
      let part = this.handleWherePart(this.mainNumb)
      // 得到这个区间的概率数组
      let odds = this.handleGetOdds(part)
      // 抽到的积分是
      let score = this.getResult(odds)
      console.log('本次抽到的积分是', score)
      this.mainNumb = this.mainNumb + score
      this.nums.push(this.mainNumb)
      console.log('结束，当前积分值为', this.mainNumb)
    },
    handleLottery (arr) {
      let array = [parseInt(arr[0]), parseInt(arr[1]), parseInt(arr[2]), parseInt(arr[3]), parseInt(arr[4]), parseInt(arr[5])]
      let total = 0
      for (let i = 0; i < array.length; i++) {
        total += array[i]
      }
      for (let j = 0; j < array.length; j++) {
        let random = parseInt(Math.random() * total)
        if (random < array[j]) {
          return j
        } else {
          total -= array[j]
        }
      }
      // return array
    },
    handleGetOdds (num) {
      const arr = [
        [
          this.inputB1.replace(' ', ''),
          this.inputC1.replace(' ', ''),
          this.inputD1.replace(' ', ''),
          this.inputE1.replace(' ', ''),
          this.inputF1.replace(' ', ''),
          this.inputG1.replace(' ', '')
        ],
        [
          this.inputB2.replace(' ', ''),
          this.inputC2.replace(' ', ''),
          this.inputD2.replace(' ', ''),
          this.inputE2.replace(' ', ''),
          this.inputF2.replace(' ', ''),
          this.inputG2.replace(' ', '')
        ],
        [
          this.inputB3.replace(' ', ''),
          this.inputC3.replace(' ', ''),
          this.inputD3.replace(' ', ''),
          this.inputE3.replace(' ', ''),
          this.inputF3.replace(' ', ''),
          this.inputG3.replace(' ', '')
        ],
        [
          this.inputB4.replace(' ', ''),
          this.inputC4.replace(' ', ''),
          this.inputD4.replace(' ', ''),
          this.inputE4.replace(' ', ''),
          this.inputF4.replace(' ', ''),
          this.inputG4.replace(' ', '')
        ],
        [
          this.inputB5.replace(' ', ''),
          this.inputC5.replace(' ', ''),
          this.inputD5.replace(' ', ''),
          this.inputE5.replace(' ', ''),
          this.inputF5.replace(' ', ''),
          this.inputG5.replace(' ', '')
        ],
        [
          this.inputB6.replace(' ', ''),
          this.inputC6.replace(' ', ''),
          this.inputD6.replace(' ', ''),
          this.inputE6.replace(' ', ''),
          this.inputF6.replace(' ', ''),
          this.inputG6.replace(' ', '')
        ],
        [
          this.inputB7.replace(' ', ''),
          this.inputC7.replace(' ', ''),
          this.inputD7.replace(' ', ''),
          this.inputE7.replace(' ', ''),
          this.inputF7.replace(' ', ''),
          this.inputG7.replace(' ', '')
        ],
        [
          this.inputB8.replace(' ', ''),
          this.inputC8.replace(' ', ''),
          this.inputD8.replace(' ', ''),
          this.inputE8.replace(' ', ''),
          this.inputF8.replace(' ', ''),
          this.inputG8.replace(' ', '')
        ],
        [
          this.inputB9.replace(' ', ''),
          this.inputC9.replace(' ', ''),
          this.inputD9.replace(' ', ''),
          this.inputE9.replace(' ', ''),
          this.inputF9.replace(' ', ''),
          this.inputG9.replace(' ', '')
        ],
        [
          this.inputB10.replace(' ', ''),
          this.inputC10.replace(' ', ''),
          this.inputD10.replace(' ', ''),
          this.inputE10.replace(' ', ''),
          this.inputF10.replace(' ', ''),
          this.inputG10.replace(' ', '')
        ]
      ]
      return arr[num]
    },
    handleWherePart (num) {
      // 输入一个数，返回所在的区间索引
      const arr = this.handleGetPart()
      for (let i = 0; i < arr.length; i++) {
        if (i === 0 && num < arr[i]) {
          return i
        } else if (i === 9 && num > arr[i]) {
          return i
        } else {
          if (num <= arr[i][1] && num > arr[i][0]) {
            return i
          }
        }
      }
    },
    handleGetPart () {
      // 返回区间数组
      let part1 = parseInt(this.inputA1.replace(' ', ''))
      let part2 = [parseInt(this.inputA2.replace(' ', '').split(',')[0]), parseInt(this.inputA2.replace(' ', '').split(',')[1])]
      let part3 = [parseInt(this.inputA3.replace(' ', '').split(',')[0]), parseInt(this.inputA3.replace(' ', '').split(',')[1])]
      let part4 = [parseInt(this.inputA4.replace(' ', '').split(',')[0]), parseInt(this.inputA4.replace(' ', '').split(',')[1])]
      let part5 = [parseInt(this.inputA5.replace(' ', '').split(',')[0]), parseInt(this.inputA5.replace(' ', '').split(',')[1])]
      let part6 = [parseInt(this.inputA6.replace(' ', '').split(',')[0]), parseInt(this.inputA6.replace(' ', '').split(',')[1])]
      let part7 = [parseInt(this.inputA7.replace(' ', '').split(',')[0]), parseInt(this.inputA7.replace(' ', '').split(',')[1])]
      let part8 = [parseInt(this.inputA8.replace(' ', '').split(',')[0]), parseInt(this.inputA8.replace(' ', '').split(',')[1])]
      let part9 = [parseInt(this.inputA9.replace(' ', '').split(',')[0]), parseInt(this.inputA9.replace(' ', '').split(',')[1])]
      let part10 = parseInt(this.inputA10.replace(' ', ''))
      return [part1, part2, part3, part4, part5, part6, part7, part8, part9, part10]
    },
    getResult (arr) {
      let index = this.handleLottery(arr)
      switch (parseInt(index)) {
        case 0:
          return 1
        case 1:
          return 5
        case 2:
          return 9
        case 3:
          return 19
        case 4:
          return 99
        case 5:
          return 669
      }
    },
    multLottery (num, arr) {
      let a1 = 0
      let a2 = 0
      let a3 = 0
      let a4 = 0
      let a5 = 0
      let a6 = 0
      for (let i = 0; i < num; i++) {
        let random = this.handleLottery(arr)
        // console.log('random', random)
        if (random === 0) {
          a1 += 1
        } else if (random === 1) {
          a2 += 1
        } else if (random === 2) {
          a3 += 1
        } else if (random === 3) {
          a4 += 1
        } else if (random === 4) {
          a5 += 1
        } else if (random === 5) {
          a6 += 1
        }
      }
      return [a1, a2, a3, a4, a5, a6]
    }
  },
  mounted () {
    // console.log(this.multLottery(10000, [3, 5, 35, 55, 2, 0]))
  }
}
</script>

<style lang="stylus" scoped>

</style>
